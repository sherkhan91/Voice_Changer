## ROBOTIC VOICE CHANGER

This is a hobby project in rust aims to provide a robotic sound when give it mp4 video or audio it will convert that sound into mp3. 

This project uses FFMPEG and rust.

## Usage

```
cargo build

cargo run ./input.mp3 outputFolder  # input file and output path

```

Once the run is complete you can able to see out.mp3 in your output folder, if you run again then remove that out.mp3 as sometime system doesn’t allow removing of that mp3


## Debug

```
RUST_LOG=debug cargo run <in> <out>

```

To run in debug mode.

