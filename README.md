# Awesome Short-Form Video [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Vertical short video for TikTok, YouTube Shorts, Instagram Reels and Facebook Reels, made with code, command-line tools or agents.

## Contents

- [Rendering video from code](#rendering-video-from-code)
- [Editing and cutting](#editing-and-cutting)
- [Clipping and pipelines](#clipping-and-pipelines)
- [Transcription and captions](#transcription-and-captions)
- [Voice](#voice)
- [Agent skills and MCP servers](#agent-skills-and-mcp-servers)
- [Specs, safe zones and templates](#specs-safe-zones-and-templates)
- [Posting and scheduling](#posting-and-scheduling)
- [Measuring](#measuring)
- [Related lists](#related-lists)

## Rendering video from code

- [Etro](https://github.com/etro-js/etro) - TypeScript library that composites video, audio, text and image layers with GLSL filters in the browser.
- [HyperFrames](https://github.com/heygen-com/hyperframes) - Renders HTML, CSS, media and seekable animations to deterministic MP4 video, with a CLI and agent skills.
- [Manim](https://github.com/3b1b/manim) - Python animation engine for explanatory math videos.
- [Manim Community](https://github.com/ManimCommunity/manim) - Community-maintained fork of Manim with its own documentation and release cycle.
- [Mediabunny](https://github.com/Vanilagy/mediabunny) - TypeScript toolkit for reading, writing and converting video and audio files in browsers, Node.js, Bun and Deno.
- [Motion Canvas](https://github.com/motion-canvas/motion-canvas) - TypeScript library that programs vector animations with generators, plus an editor with live preview.
- [MoviePy](https://github.com/Zulko/moviepy) - Python library for cutting, joining, compositing and titling video.
- [Remotion](https://github.com/remotion-dev/remotion) - Renders videos from React components. For-profit organizations with over three employees need a company license for commercial use.
- [Revideo](https://github.com/midrender/revideo) - TypeScript engine for scenes written in code, with a headless render API and a React player.

## Editing and cutting

- [auto-editor](https://github.com/WyattBlue/auto-editor) - Cuts silence and dead space by audio loudness, then exports a video or a Premiere or Resolve timeline.
- [FFmpeg](https://github.com/FFmpeg/FFmpeg) - Command-line tool and libraries that convert, cut, crop, scale, filter and encode video and audio.
- [ffmpeg-normalize](https://github.com/slhck/ffmpeg-normalize) - Batch-normalizes audio loudness with FFmpeg using the EBU R128 procedure.
- [ffmpeg-vertical-video](https://github.com/viewgum/ffmpeg-vertical-video) - Tested FFmpeg commands for 9:16 video, each run in CI and checked with ffprobe (by the maintainers).
- [ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm) - FFmpeg compiled to WebAssembly for recording, converting and processing media in the browser.
- [LosslessCut](https://github.com/mifi/lossless-cut) - Desktop app that trims, cuts and merges video and audio without re-encoding.
- [MLT](https://github.com/mltframework/mlt) - Multimedia framework behind Shotcut and Kdenlive, with the melt command-line tool for scripted edits.
- [PySceneDetect](https://github.com/Breakthrough/PySceneDetect) - Detects cuts and transitions and splits video into scenes, from the command line or Python.

## Clipping and pipelines

- [FunClip](https://github.com/modelscope/FunClip) - Local clipping tool that transcribes with FunASR and cuts by text, speaker or LLM picks; Chinese first.
- [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) - Makes a short from a topic: script, stock footage, voiceover, subtitles and music.
- [OpenShorts](https://github.com/mutonby/openshorts) - Self-hostable app that finds moments in long videos, reframes them to 9:16 and adds captions.

## Transcription and captions

- [Aegisub](https://github.com/TypesettingTools/Aegisub) - Subtitle editor for timing and styling ASS captions, including karaoke effects.
- [Argmax Open-Source SDK](https://github.com/argmaxinc/argmax-oss-swift) - Swift frameworks for on-device speech-to-text with WhisperKit, plus speaker diarization, on Apple devices.
- [AutoSubs](https://github.com/tmoroney/auto-subs) - Local subtitle generation as a desktop app or inside DaVinci Resolve, Premiere Pro and After Effects.
- [Buzz](https://github.com/chidiwilliams/buzz) - Desktop app that transcribes and translates audio offline with Whisper.
- [faster-whisper](https://github.com/SYSTRAN/faster-whisper) - Whisper on CTranslate2 for faster transcription with less memory, including word timestamps.
- [FFmpeg subtitles filter](https://ffmpeg.org/ffmpeg-filters.html#subtitles-1) - Burns SRT or styled ASS captions into video, using libass.
- [ffsubsync](https://github.com/smacke/ffsubsync) - Shifts a subtitle file to match the audio of a video automatically.
- [libass](https://github.com/libass/libass) - Renderer for styled ASS and SSA subtitles, used by FFmpeg and many players.
- [pysubs2](https://github.com/tkarabela/pysubs2) - Python library for editing SRT, ASS and other subtitle files.
- [Remotion TikTok template](https://github.com/remotion-dev/template-tiktok) - Transcribes with whisper.cpp for word captions. For-profit organizations with over three employees need a company license for commercial use.
- [short-form-captions](https://github.com/viewgum/short-form-captions) - Turns word timestamps into SRT, WebVTT or ASS captions inside the safe zone and checks reading speed (by the maintainers).
- [Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit) - Subtitle editor with speech-to-text, syncing, translation and conversion between formats.
- [Whisper](https://github.com/openai/whisper) - OpenAI's open speech recognition model for transcription and translation in many languages.
- [whisper.cpp](https://github.com/ggml-org/whisper.cpp) - C and C++ port of Whisper that runs on CPUs and GPUs without Python.
- [WhisperX](https://github.com/m-bain/whisperX) - Whisper transcription with forced alignment for word timestamps, plus speaker diarization.

## Voice

Model weights can carry a different license from the code, so check both before commercial use.

- [Coqui TTS](https://github.com/idiap/coqui-ai-TTS) - Multilingual speech synthesis and voice cloning library. XTTS-v2 model weights and outputs are for non-commercial use.
- [CosyVoice](https://github.com/QwenAudio/CosyVoice) - Multilingual text-to-speech with zero-shot voice cloning, emotion and speed instructions, and streaming output.
- [F5-TTS](https://github.com/SWivid/F5-TTS) - Flow-matching text-to-speech that clones a voice from a short sample; pretrained weights are non-commercial.
- [Fish Speech](https://github.com/fishaudio/fish-speech) - Multilingual text-to-speech and voice cloning with a command line, API server and web UI; custom license.
- [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) - Few-shot voice cloning and text-to-speech web UI that can train on about a minute of audio.
- [IndexTTS](https://github.com/index-tts/index-tts) - Zero-shot voice cloning with emotion, speed and pronunciation control; custom model license.
- [Kitten TTS](https://github.com/KittenML/KittenTTS) - Text-to-speech models from 7M parameters that run on a CPU, plus a larger model with voice cloning.
- [Kokoro-FastAPI](https://github.com/remsky/Kokoro-FastAPI) - OpenAI-compatible speech server for the Kokoro-82M model, packaged in Docker for CPU or GPU.
- [NeuTTS](https://github.com/neuphonic/neutts) - On-device voice cloning. Air uses Apache 2.0. Nano and 2E use the NeuTTS Open License 1.0.
- [Piper](https://github.com/OHF-Voice/piper1-gpl) - Local neural text-to-speech engine with a command line, web server and Python API.
- [Pocket TTS](https://github.com/kyutai-labs/pocket-tts) - Kyutai's small CPU text-to-speech model; Kyutai reports about six times real time on an M4 MacBook Air.
- [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS) - Qwen's open text-to-speech models with voice cloning, voice design from a description and streaming.
- [VibeVoice](https://github.com/microsoft/VibeVoice) - Microsoft's open voice models, including a realtime 0.5B text-to-speech model and long-form speech recognition.

## Agent skills and MCP servers

- [CutVoke](https://github.com/frankShan001/CutVoke) - Local-first desktop video editor with a built-in MCP server, so agents and people edit the same multi-track timeline.
- [DaVinci Resolve MCP](https://github.com/samuelgursky/davinci-resolve-mcp) - MCP server that drives DaVinci Resolve Studio through its scripting API: editing, media, render setup and grading.
- [HyperFrames skills](https://github.com/heygen-com/hyperframes/tree/main/skills) - Agent skills for writing, previewing and rendering HyperFrames videos from Claude Code, Codex, Cursor or Gemini CLI.
- [Kinocut](https://github.com/KyaniteLabs/kinocut) - Local MCP server and CLI that gives agents checked FFmpeg editing tools, quality gates and an edit record.
- [MCP for Blender](https://github.com/ahujasid/mcp-for-blender) - Connects Blender to MCP clients so an agent can create and change 3D scenes, objects and materials.
- [Remotion skills](https://github.com/remotion-dev/skills) - Remotion's agent skills for creating, previewing and rendering projects, including captions and map animations.
- [ViewGum short-form specs skill](https://github.com/viewgum/skills/tree/main/skills/short-form-specs) - Agent skill with the four apps' 9:16 ad-placement safe zones, length limits and caption limits (by the maintainers).
- [YouTube MCP Server](https://github.com/ZubeidHendricks/youtube-mcp-server) - Retrieves video, channel and playlist metadata through the YouTube Data API and available transcripts through youtube-transcript.

## Specs, safe zones and templates

- [Facebook Reels ad specs](https://www.facebook.com/business/ads-guide/update/video/facebook-facebook-reels) - Meta's file type, ratio, codec and length guidance for video on Facebook Reels.
- [Instagram Reels ad specs](https://www.facebook.com/business/ads-guide/update/video/instagram-reels) - Meta's file type, ratio, codec and length guidance for video on Instagram Reels.
- [Instagram Reels guide](https://about.instagram.com/features/reels) - Instagram's guide to recording and editing Reels up to 20 minutes long.
- [Meta text overlays and safe zones](https://www.facebook.com/business/help/980593475366490) - Meta's guidance on keeping text clear of the app interface in Stories and Reels.
- [short-form-video-specs](https://github.com/viewgum/short-form-video-specs) - Pixel measurements and PNG templates for four apps' 9:16 ad-placement safe zones (by the maintainers).
- [TikTok in-feed ad specs](https://ads.tiktok.com/help/article/tiktok-auction-in-feed-ads) - TikTok's ratio, resolution, file type, length and caption limits for in-feed video.
- [YouTube Shorts help](https://support.google.com/youtube/answer/10059070?hl=en) - YouTube's guide to making and uploading Shorts.
- [YouTube Shorts length](https://support.google.com/youtube/answer/15424877?hl=en) - Which square and vertical uploads count as Shorts, up to three minutes long.
- [YouTube upload encoding settings](https://support.google.com/youtube/answer/1722171?hl=en) - YouTube's recommended container, codecs, bitrates and frame rates for uploads.

## Posting and scheduling

- [Facebook Reels Publishing API](https://developers.facebook.com/documentation/video-api/guides/reels-publishing) - Meta's API for uploading and publishing Reels to a Facebook Page, with its video specs.
- [Instagram content publishing](https://developers.facebook.com/documentation/instagram-platform/content-publishing) - Meta's guide to publishing Reels, images and carousels to professional Instagram accounts.
- [Postiz](https://github.com/gitroomhq/postiz-app) - Self-hostable social media scheduler with TikTok, YouTube, Instagram, Facebook and other integrations.
- [TikTok Content Posting API](https://developers.tiktok.com/docs/en/content-posting-api-get-started) - Direct Post publishes a video to an account; unaudited apps can post only privately.
- [TikTok Content Posting API, upload](https://developers.tiktok.com/docs/en/content-posting-api-get-started-upload-content) - Uploads a video as a draft the creator finishes and posts in the TikTok app.
- [TikTok media transfer guide](https://developers.tiktok.com/docs/en/content-posting-api-media-transfer-guide) - File upload, chunk and pull-from-URL rules for sending video to TikTok's API.
- [YouTube Data API videos.insert](https://developers.google.com/youtube/data/reference/rest/v3/videos/insert) - YouTube's API method for uploading a video with its title, description, tags and privacy status.
- [YouTube quota calculator](https://developers.google.com/youtube/data/determine_quota_cost) - Quota cost of each YouTube Data API method, including uploads.
- [YouTube resumable uploads](https://developers.google.com/youtube/data/guides/using_resumable_upload_protocol) - How to upload large video files to YouTube in resumable chunks.

## Measuring

- [Facebook video insights](https://developers.facebook.com/documentation/video-api/guides/insights) - How to read metrics for videos and Reels published on a Facebook Page.
- [Instagram media insights](https://developers.facebook.com/documentation/instagram-platform/reference/instagram-media/insights) - Metrics for one Instagram post or Reel, such as views, reach, likes and shares.
- [TikTok Display API](https://developers.tiktok.com/docs/en/display-api-overview) - Reads a creator's profile and public videos with view, like, comment and share counts, with permission.
- [YouTube Analytics and Reporting APIs](https://developers.google.com/youtube/analytics) - YouTube's APIs for channel and video metrics, as targeted queries or bulk daily reports.
- [YouTube Analytics metrics](https://developers.google.com/youtube/analytics/metrics) - Definitions of YouTube Analytics metrics such as views, engaged views and average view duration.

## Related lists

- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Model Context Protocol servers by category, including multimedia processing.
- [Awesome Small Business Video](https://github.com/viewgum/awesome-small-business-video) - Official, free resources for small businesses making short vertical videos (by the maintainers).
- [Awesome Video](https://github.com/krzemienski/awesome-video) - Streaming video tools, frameworks, libraries and learning resources.
- [Awesome Whisper](https://github.com/sindresorhus/awesome-whisper) - Tools, apps and models built around OpenAI's Whisper speech recognition.

## Contributing

Read the [contribution guidelines](CONTRIBUTING.md) before you open a pull request.

## Footnotes

Every link was checked on 2026-11-19 (data/checked-2026-11-19.json) or, for a later entry, on the day it was added, and every GitHub repository was active within the 12 months before that day. A monthly job checks them again.

Maintained by [ViewGum](https://viewgum.com), a short-form video maker. Entries by the maintainers are marked.
