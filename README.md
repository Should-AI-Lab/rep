# GRID: Video Generation Model Comparison

This repository compares GRID (our model) with other state-of-the-art video generation models including AnimateDiffV3, VideoCrafter2, and CogVideo5B.

## Portrait Video Comparison

**Prompt:** "A woman with glasses wearing a white t-shirt sits at a wooden desk. An open notebook and calculator lie before her. She examines the document then picks up a pen. She wears bracelets on her wrist. Home study setting with natural light."

<div align="center">
<table>
  <tr>
    <td align="center"><b>GRID (Ours)</b></td>
    <td align="center"><b>AnimateDiffV3</b></td>
  </tr>
  <tr>
    <td><a href="./static/1.mp4"><img src="https://github.com/USERNAME/REPO-NAME/raw/BRANCH-NAME/assets/grid_portrait_thumbnail.jpg" width="100%"></a></td>
    <td><img src="./static/0-A-woman-with-glasses-wearing-a-white-t-shirt-sits-at.gif" width="100%"></td>
  </tr>
  <tr>
    <td align="center"><b>VideoCrafter2</b></td>
    <td align="center"><b>CogVideo5B</b></td>
  </tr>
  <tr>
    <td><a href="./static/vcver-0001.mp4"><img src="https://github.com/USERNAME/REPO-NAME/raw/BRANCH-NAME/assets/videocrafter_portrait_thumbnail.jpg" width="100%"></a></td>
    <td><a href="./static/cogvideo.mp4"><img src="https://github.com/USERNAME/REPO-NAME/raw/BRANCH-NAME/assets/cogvideo_portrait_thumbnail.jpg" width="100%"></a></td>
  </tr>
</table>
</div>

## Landscape Video Comparison

**Prompt:** "Elegant European city street with curved row of sandstone historical buildings, arched entrances, uniform windows, neoclassical architectural style, parked cars, few pedestrians, camera slowly moving forward."

<div align="center">
<table>
  <tr>
    <td align="center"><b>GRID (Ours)</b></td>
    <td align="center"><b>AnimateDiffV3</b></td>
  </tr>
  <tr>
    <td><a href="./static/2.mp4"><img src="https://github.com/USERNAME/REPO-NAME/raw/BRANCH-NAME/assets/grid_landscape_thumbnail.jpg" width="100%"></a></td>
    <td><img src="./static/0-Elegant-European-city-street-with-curved-row-of-sandstone-historical.gif" width="100%"></td>
  </tr>
  <tr>
    <td align="center"><b>VideoCrafter2</b></td>
    <td align="center"><b>CogVideo5B</b></td>
  </tr>
  <tr>
    <td><a href="./static/vc-0002.mp4"><img src="https://github.com/USERNAME/REPO-NAME/raw/BRANCH-NAME/assets/videocrafter_landscape_thumbnail.jpg" width="100%"></a></td>
    <td><a href="./static/cog2.mp4"><img src="https://github.com/USERNAME/REPO-NAME/raw/BRANCH-NAME/assets/cogvideo_landscape_thumbnail.jpg" width="100%"></a></td>
  </tr>
</table>
</div>

## Long Video Comparison (128 frames)

<div align="center">
<table>
  <tr>
    <td align="center"><b>GRID (Ours)</b></td>
    <td align="center"><b>CogVideo5B</b></td>
  </tr>
  <tr>
    <td><a href="./static/128.mp4"><img src="https://github.com/USERNAME/REPO-NAME/raw/BRANCH-NAME/assets/grid_long_thumbnail.jpg" width="100%"></a></td>
    <td><a href="./static/cog2long128.mp4"><img src="https://github.com/USERNAME/REPO-NAME/raw/BRANCH-NAME/assets/cogvideo_long_thumbnail.jpg" width="100%"></a></td>
  </tr>
</table>
</div>

## About the Models

- **GRID**: Our proposed model for high-quality video generation
- **AnimateDiffV3**: Text-to-video diffusion model
- **VideoCrafter2**: Advanced video generation framework
- **CogVideo5B**: Large-scale video generation model

---

### Video Playback

Click on the thumbnails to download and view the video files. GIF animations display automatically.

To view all videos in full quality:
- [GRID Portrait Video](./static/1.mp4)
- [VideoCrafter2 Portrait Video](./static/vcver-0001.mp4)
- [CogVideo5B Portrait Video](./static/cogvideo.mp4)
- [GRID Landscape Video](./static/2.mp4)
- [VideoCrafter2 Landscape Video](./static/vc-0002.mp4)
- [CogVideo5B Landscape Video](./static/cog2.mp4)
- [GRID Long Video](./static/128.mp4)
- [CogVideo5B Long Video](./static/cog2long128.mp4)
