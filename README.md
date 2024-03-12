# Parsing MiniLang

This project contains a recursive descent parser for the MiniLang programming language. MiniLang supports basic constructs like arithmetic, variables, conditional statements, and printing. 

## Usage

To use the MiniLang parser:

### Clone the repo
```
git clone https://github.com/your-username/minilang-parser.git
cd minilang-parser
```

### Run the parser 
```
python minilang_parser.py <filepath>
```
Replace `<filepath>` with the MiniLang source file path.

## Language Specs

MiniLang supports:

- Arithmetic 
- Variable assignment
- If/else conditions
- Print statements

## Parser Details

### Type
The MiniLang parser uses recursive descent parsing, suitable for LL grammars. This approach keeps the implementation simple.