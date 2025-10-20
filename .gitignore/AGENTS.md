# Agent Guidelines - C Language Project Template

## Build & Run Commands
```bash
cd "3_소스코드"
gcc main.c -o my_project        # Compile
./my_project                     # Run (Linux/Mac)
my_project.exe                   # Run (Windows)
gcc -Wall -Wextra main.c -o my_project  # Compile with warnings
```

## Code Style
- Language: C (C99 or later standard)
- Indentation: 4 spaces (follow existing template style)
- Use `struct` for data structures (e.g., `struct Student`)
- Function names: lowercase with underscores (e.g., `add_student`, `search_student`)
- Include `<stdio.h>` and other standard libraries as needed
- Error handling: Check array bounds, validate user input with `if` conditions
- Comments: Korean comments allowed per template; use `/* */` for documentation

## Project Structure
- `1_설계/설계서.md` - Design document (functions, structs, features)
- `2_알고리즘/의사코드.md` - Pseudocode/algorithm logic
- `3_소스코드/main.c` - Main implementation file
- `4_디버깅/디버깅_보고서.md` - Debugging report (track all errors/fixes)

## Important Notes
- Follow template structure: declare structs globally, then functions, then `main()`
- Always validate input (especially `scanf` buffer issues with `while(getchar() != '\n');`)
- Document all bugs found and solutions in `4_디버깅/디버깅_보고서.md`
- Code must be explainable by the student (code interview requirement)
