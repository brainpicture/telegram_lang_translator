# Translation Script for telegram style langpacks

## Overview
This script utilizes ChatGPT to generate a JSON file containing translations into a specified language. It is designed to be executed with bun.sh, a part of the Bun JavaScript runtime.

The core concept of this script lies in its ability to leverage pre-existing translations across multiple languages to generate a translation for a new language.

Do not forget to add you OpenAI key in translate.js

## Prerequisites
Before using this script, ensure that you have bun installed on your system. Bun can be quickly installed through their official instructions found at: https://bun.sh/. Installation is a prerequisite, as the script relies on Bun's JavaScript runtime environment.

## Usage
To use the script, run the following command:
bun translate.js <language>

Replace <language> with the appropriate language (Armenian, Italian, etc).

## Output
After running the command, the script will create a new file with the language code as its filename extension (e.g., hy.xml). This file will be populated with all the translations, updating keys incrementally as each translation is processed.

The creation of this file facilitates the use of translations for various applications that require localization support.

## Example
To generate an Armenian translation file, execute the command:
```bun translate.js armenian```

Upon successful execution, a new file named hy.xml will be created in the current directory.

## Support
If you encounter any issues or require assistance with the translation script or Bun, please consult the Bun documentation or reach out to the community for support.

## License
Please ensure that you comply with the relevant licenses for using ChatGPT and Bun when utilizing this script for translations.