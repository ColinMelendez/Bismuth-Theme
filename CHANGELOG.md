# Change Log

## [Released-Beta]

The theme is still not what I would call "finished" even though it has more total features than most themes. I anticipate somewhat significant evolutions to continue, though from here on, all major distinct versions will be kept live.

- 0.7.11: fixed underspecified "variable.other.object" selector
- 0.7.9: added missing importmeta keyword
- 0.7.8: improved coloring consistency of lifetime annotation and the self keyword across textmate and semantic schemes
- 0.7.6: fixed improper italicization for | in yaml
- 0.7.5: fixed some overlooked nix operator and punctuation tokens, and missing typescript infer keyword
- 0.7.2: Fixed outdated extension metadata
- 0.7.0: Returned to the original warm background color
- 0.6.7: Added some missing class scope operators that are general to many languages, and tweaked description
- 0.6.6: Added support for .log file syntax
- 0.6.5: Expanded coverage and increased specificity for operators and some edge scopes of bash, and added coverage for CSS gradient operators
- 0.6.3: Expanded coverage of C and C++ memory operators and added support for Java package keywords
- 0.6.1: Fixed the assignments of the "rest" and "spread" operators so that they both match other common operators
- 0.6.0: Added support for CSS units and keywords, and fixed some inconsistent typescript edge cases
- 0.5.5: Added support for makefile recipes and prerequisites, expanded Go semantic token coverage
- 0.5.1: Fixed a bug with Go imports not being colored correctly with semantic tokens.
- 0.5.0: Public Release! Added theme elements for bracket pairs, outline symbols, menus, errors, and matching colors for errorLens, among other consistency tweaks.
- Initial release --------------------
- 0.4.0: More specific coverage added for Go and Rust Semantic tokens and language nuances. Switched to a dark and uniform base background
- 0.3.0: Color overhaul for strings, objects, and strings (just for code - ui is NOT matching the changes at this time). The colors were made less intense and very slightly more faded. Also, walked-back the rust-colors for namespaces. They now match the objects/classes/interfaces/structs in color, but remain underlined as a quick distinction.
- 0.2.0: Updated the special keyword operators ( arrows(->, =>), assignment(=), new, reference(&) ) to be non-italic for less overall italics in the theme. Also reduced the saturation of their purple color.