# Sharpen Before or After Upscaling? The Order Survives Float, Not a File

Sharpening a low-res frame then upscaling matches sharpening after the upscale to within 0.002 dB in float — and loses to it in all 12 real-image cases once an 8-bit or JPEG step sits between the two operations. Measured on 4 distinct photographs at 2x, 3x and 4x.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-sharpen-before-or-after-upscale/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
