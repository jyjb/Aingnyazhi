
---

## வளர்ச்சி திட்டம் (Development Plan)

### கட்டம் 1: ஆரம்ப Compiler (C)

நோக்கம்:
- Aaythamm மொழியில் எழுதப்பட்ட ஒரு எளிய நிரலை compile செய்து இயக்குதல்

பகுதிகள்:
- Lexer (token உருவாக்கம்)
- Parser (AST உருவாக்கம்)
- அடிப்படை AST
- Semantic analysis
- LLVM code generation

---

### கட்டம் 2: அடிப்படை மொழி அம்சங்கள்

சேர்க்கப்படும் அம்சங்கள்:
- Primitive types
- Variables
- Expressions
- Conditional statements (`என்றால்`)
- Loops
- அடிப்படை library

---

### கட்டம் 3: Memory & Safety

- Ownership model
- Move semantics
- Borrowing (ஆரம்ப நிலை)
- Lifetime checks

---

### கட்டம் 4: Systems Programming

- Structs
- Pointers
- Direct memory access
- `no_std` mode

---

### கட்டம் 5: Self-hosting

- Compiler-ஐ Aaythamm-ல் எழுதுதல்
- Aaythamm compiler → Aaythamm compiler compile செய்யும் நிலை

---

### கட்டம் 6: Ecosystem

- Standard library
- Package manager
- Tools (formatter, linter)

---

### கட்டம் 7: நீண்டகால இலக்குகள்

- Operating System development
- Robotics & automation
- CNC / Industrial systems
- AI / ML runtime
- LLM support

---

## இலக்கு தளங்கள் (Target Platforms)

ஆரம்பம்:
- Linux (x86_64)

பின்னர்:
- Windows
- ARM architectures
- Embedded systems

---

## சவால்கள்

- Compiler உருவாக்கத்தின் சிக்கல்
- C-ல் memory bugs ஏற்படும் அபாயம்
- Scope அதிகரிப்பு
- Cross-platform compatibility

---

## வழிகாட்டும் கொள்கைகள்

- Core language எளிமையாக இருக்க வேண்டும்
- தேவையற்ற abstraction தவிர்க்க வேண்டும்
- Correctness > Features
- Incremental development
- நீண்டகால பராமரிப்பு

---

## முடிவு

**ஆய்தம்** என்பது ஒரு நீண்டகால முயற்சி.  
இது ஒரு முழுமையான, உயர் செயல்திறன் கொண்ட, தமிழ் அடிப்படையிலான systems programming language ஆக உருவாக்கப்படுகிறது.

இந்த மொழி எதிர்காலத்தில் OS, hardware, மற்றும் AI துறைகளில் முக்கிய பங்கு வகிக்கும் வகையில் வடிவமைக்கப்படுகிறது.
