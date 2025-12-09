# 0x06. Regular Expressions

Regular expressions (regex) are powerful tools for pattern matching and text processing.  
This project focuses on writing Ruby scripts that use **Oniguruma**, the regex engine used by Ruby by default.

## Project Overview

Each task requires creating a Ruby script that takes one argument from the command line and applies a regular expression to it:

```bash
./script_name.rb <input_string>
Each script follows this template:
#!/usr/bin/env ruby
puts ARGV[0].scan(/your_regex/).join

Environment
----------------
OS: Ubuntu 20.04 LTS
Language: Ruby
Regex Engine: Oniguruma
Editors Allowed: vi, vim, emacs
All scripts must be executable and must end with a new line.

Directory Structure:
---------------------------
0x06-regular_expressions/
│
├── 0-simply_match_school.rb
├── 1-repetition_token_0.rb
├── 2-repetition_token_1.rb
├── 3-repetition_token_2.rb
├── 4-repetition_token_3.rb
├── 5-beginning_and_end.rb
├── 6-phone_number.rb
├── 7-OMG_WHY_ARE_YOU_SHOUTING.rb
└── README.md
