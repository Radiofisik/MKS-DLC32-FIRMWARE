# Claude Code Configuration

This is the configuration file for Claude Code in the MKS DLC32 firmware project.

## Project Overview
MKS DLC32 firmware project for laser engraving/cutting controller.

## Build Commands
- Build: `platformio run`
- Upload: `platformio run --target upload`
- Clean: `platformio run --target clean`

## Lint/Format Commands
- Check: `platformio check`
- Format: `clang-format -i Firmware/src/**/*.cpp Firmware/src/**/*.h`

## Test Commands
- Test: `platformio test`

## Project Structure
- `Firmware/` - Main firmware source code
- `Firmware/src/` - Source files
- `Firmware/include/` - Header files
- `platformio.ini` - PlatformIO configuration

## Development Notes
- This is a PlatformIO-based firmware project
- Target hardware: MKS DLC32 controller board
- Framework: Arduino/ESP32