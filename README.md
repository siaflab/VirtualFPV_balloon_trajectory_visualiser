VirtualFPV
===
Space Moere Project balloon trajectory realtime visualizer, simulator, log viewer

## REQUIREMENT

Mac OS X, Windows 64bit with high spec GPU

## FEATURES

- Balloon trajectory realtime visualize via OSC message
- Simulation data file visualize (CUSF Landing Predictor http://predict.habhub.org/ )
- Demo mode: trajectory log file visualize

## DEPENDENCIES

- [Standard Assets](https://docs.unity3d.com/Manual/HOWTO-InstallStandardAssets.html)
- [Post Processing stack](https://assetstore.unity.com/packages/essentials/post-processing-stack-83912)
- [UnityOSC](https://github.com/jorgegarcia/UnityOSC)

## OSC Interface

Port Number: 32000

| command | description | example |
----|----|----
| /data | realtime trajectory visualize | /data "1,1,-42,03:30:00,43.126652,141.430371,6M,\x00\r\n" |
| /reset | reset command | /reset |
| /sim | simulation trajectory command | /sim "1503342000,43.1221,141.426,62" |
| /simclear | clear simulation trajectory | /simclear |

## CREDIT
VirtualFPV program licensed under MIT License.  
https://github.com/siaflab/VirtualFPV_balloon_trajectory_visualiser

Space Moere Project  
ARTSAT x SIAF Lab  
http://space-moere.org

3D/2D map licensed by
The Geospatial Information Authority of Japan  
https://maps.gsi.go.jp/
