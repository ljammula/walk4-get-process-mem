# Agent instructions

This repository is the `get_process_mem` Ruby gem. Library code lives under `lib/` and tests under `test/`.

## Verification

- Run `ruby -Ilib test/get_process_mem_test.rb` after changing the library or tests.
- Keep platform-specific behavior explicit; Linux, macOS, and Windows use different memory sources.
- Avoid requiring a live process other than the test process and its short-lived fixtures.
