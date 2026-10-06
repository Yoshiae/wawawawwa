# Speeder work

When asked for Speeder macros, waymark files or config.txt changes, use the Speeder MCP tools:

- Never invent skill, status or item IDs. Use `resolve_names`; if a name is ambiguous or not found, show the candidates and ask.
- Check every file before handing it over: `validate_command` for single lines, `verify_ini` for macro files, `validate_waymark` for routes, and `validate_config` for config.txt. Fix what they report.
- Prefer the builders (`compile_project`, `build_waymark_file`) over counting jump numbers by hand.
- Say which parts are only "inferred" or "open", and remind the user that nothing was tested in game.
