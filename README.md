# Dactyl CC plus (6x7 with RUS/LAT buttons) Keyboard ZMK Configuration

## Introduction

Based on [TaikoHub Dactyl Manuform](https://taikohub.com), but 6x7.

## Instructions

1. Fork this repo.
2. Clone the forked repo to your local machine.
   ```bash
   # replace yourusername with your Github username
   git clone https://github.com/yourusername/zmk-config.git
   ```
3. Git checkout the branch that matches your keyboard size.
   ```bash
   # Size large (6 keyed-thumb cluster)
   git checkout large
   # Size medium (5 keyed-thumb cluster)
   git checkout medium
   # Size small (3 keyed-thumb cluster)
   git checkout small
   ```
4. Open the `config/dactyl_manuform_5x6.keymap` to edit the keyboard layout.
   ```bash
   cd zmk-config
   code config/dactyl_manuform_5x6.keymap
   ```
5. Once you are done, commit and push the change.
   ```bash
   git commit -m "Update keymap"
   git push
   ```
6. Go to your Github repo and check the Actions tab. You should see a new workflow run. Once the workflow is complete, you should see a new firmware file in the `artifacts` section. Download the `firmware.zip` file.
