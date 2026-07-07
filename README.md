# Masters of PixInsight V8 Scripts

PixInsight scripts ported to the V8 JavaScript engine for full compatibility
with PixInsight 1.9.4 Lockhart, including the native Apple Silicon (ARM64) build.

**www.mastersofpixinsight.com**

## Installing via PixInsight Update System

1. In PixInsight, go to **Resources > Updates > Manage Repositories**
2. Click **Add**
3. Enter this URL:
   ```
   https://MoPScripts.github.io/mop-v8-scripts/
   ```
4. Click **OK**, then go to **Resources > Updates > Check for Updates**
5. Select **MoPV8Scripts** and click **Install**
6. Scripts will appear under **Script > MoP V8** in the menu

## Scripts Included

| Script | Description |
|--------|-------------|
| AberrationInspector_V8 | Builds an n×n mosaic for inspecting optical aberrations |
| AutoColor_V8 | Automatic background neutralization and color calibration |
| Batch_Fits_Keyword_Modifier_V8 | Batch modify FITS keywords across multiple files |
| Batch_Rename_Files_V8 | Batch rename files by text string |
| CanonBandingReduction_V8 | Reduces horizontal banding in Canon DSLR images |
| Combine_Two_Views_V8 | Combine two views with multiple blend modes |
| DBXtract_V8 | Extract narrowband signal from dual-band filters and OSC cameras |
| DarkStructureEnhance_V8 | Enhances dark structures using wavelet scaling, with preview |
| DrawSignature_V8 | Draws a text signature onto an image corner |
| GAME_V8 | Interactive galaxy mask editor with elliptical and multi-point regions |
| ImageInsert_V8 | Inserts a smaller image into a corner of a larger image |
| NBRGBCombination_V8 | Combines narrowband data with RGB using per-channel weighting |
| PreviewAggregator_V8 | Combines multiple previews into a single comparison image |
| RatioCrop_V8 | Ratio-locked crop with joystick pad positioning |
| Remove_AutoCrop_Views_V8 | Removes WBPP autocrop borders and saves clean ACR master files |
| Save_Selected_Views_V8 | Save selected views to disk |
| SyntheticLuminance_V8 | Creates synthetic luminance from RGB channels |

## Updates

When Pete releases updated scripts, PixInsight will notify you automatically
via **Resources > Updates > Check for Updates**.

## Credits

Original scripts by their respective authors — all copyright notices preserved.
V8 ports by Peter Proulx, Masters of PixInsight.
