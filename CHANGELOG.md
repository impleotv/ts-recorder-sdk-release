Change Log
==========
### Ver. 1.0.26 (11/05/23)
- I frame manifest for HEVC
### Ver. 1.0.25 (11/05/23)
- Fix HEVC Intra refresh HLS recording
### Ver. 1.0.24 (17/11/21)
- Move to v142 target and runtime
- Boost v142
- Add support for KlvPlayer's recording mode license
 
### Ver. 1.0.22 (18/05/21)
- Fix empty copyOutputLocation 

### Ver. 1.0.21 (12/05/21)
- Fix mpeganalizer

### Ver. 1.0.20 (12/05/21)
- Fix mpeganalizer file lock
### Ver. 1.0.19 (11/05/21)
- Changes on last segment completion 
### Ver. 1.0.18 (06/05/21)
- Fix Iframe  manifest event fixFix typo (event ProcessingComplete)
- Various changes

### Ver. 1.0.18 (06/05/21)
- Fix Iframe  manifest event fixFix typo (event ProcessingComplete)
- Various changes

### Ver. 1.0.17.4 (04/05/21)
- Fix typo (event ProcessingComplete)
- Ensure IFrame manifest is deleted in case only empty segments were recorded
- Update documentation

### Ver. 1.0.17.3 (30/04/21)
- HLS processing completion 

### Ver. 1.0.17.2 (27/04/21)
- Add fallback detection
### Ver. 1.0.17.1 (26/04/21)
- Support packets without PTS
- Try to create remote directory, if it doesn't exist
- Add missing reference to HLS demo app

### Ver. 1.0.17.0 (25/04/21)
- Add remote target (copyOutputLocation)

### Ver. 1.0.16.3 (20/04/21)
- Add recorder instance name to Hls demo app

### Ver. 1.0.16.2 (13/04/21)
- Configurable recording time

### Ver. 1.0.16.1
- Add cmd arguments to the demo app

### Ver. 1.0.16
- Add SplitSegmentOnHlsDiscontinuity property 
- IFrameManifest SegmentFinalized change (receives list of segments)

### Ver. 1.0.15.1
- Fix negative duration

### Ver. 1.0.15
- Add detection info event (HlsSegmentInfo) 
- Add option (DeleteEmptySegments property) to remove emty segments automatically

### Ver. 1.0.14 (21/03/21)
- Remove ManifestByteRange and MasterManifest dependency. Now they may be set independently.

### Ver. 1.0.13
- Use video duration for hls

### Ver. 1.0.12.3 (08/02/21)
- Add HlsDiscontinuityDetected

### Ver. 1.0.12.2
- Fix MpegTransportAnalyzerLib.dll

### Ver. 1.0.12.1
- Fix stop hang without source

### Ver. 1.0.12
- Increase socket buffer size

### Ver. 1.0.11.1
- Increase buffer size

### Ver. 1.0.10
- I frame only manifest creation changes
### Ver. 1.0.9
- Replace boost asio with Win socket

### Ver. 1.0.8
- Make sure maniferst in not updated after it is finalized
- Master manifest and I frame manifest generation

### Ver. 1.0.7.1
- Fix exception in ts recording 

### Ver. 1.0.7.0
- Add Error handling

### Ver. 1.0.6
- Rebuild

### Ver. 1.0.5
- VC141 and Boost 1.71

### Ver. 1.0.4
- New setup 
- HLS support added
