gemini
====

NAME
----
gemini -- tiny bundler wrapper

USAGE
----
```
 * gemini [bundle-install] # Considerate `bundle install` (Accept env `gemini_path` and `gemini_binstubs`)
 * gemini [-h|--help]      # Show this help.
 * gemini [-j|--dry-run]   # Show bundle install plot (No installation is performed)
 * gemini [-v|--verbose]   # Considerate bundle install with verbose.
 * gemini [--force]        # force config (path and bin), and exec `gemini bundle-install`.
 * gemini version          # Show gemini version info.
 * gemini purge            # Clean up `.bundle`, boilerplatings and bundled-files
 * gemini clean            # Clean up boilerplatings and bundled files
 * gemini set-config       # Set bundle config (Accept env `gemini_path` and `gemini_binstubs`)
 * gemini show-config      # Show bundle config
 * gemini install-bundler  # exec `gem install bundler`
```


Author

Copyright (c) 2020 Hiroshi IKEGAMI

MIT License

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



