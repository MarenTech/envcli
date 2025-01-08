## Installation

Install EnvCLI globally using npm:

```bash
npm install -g envcli
```

## Features

- 🚀 Easy environment variable management
- 🎯 Type support (string, boolean, number, array)
- 📝 JSON-based storage
- 🎨 Colorful terminal output
- 🔄 Simple CRUD operations

## Usage

### Set Environment Variables
```bash
envcli set <key> <value> [--type=string|boolean|number|array]
```

Example:
```bash
envcli set API_URL https://api.example.com
envcli set DEBUG true --type=boolean
envcli set PORT 3000 --type=number
envcli set ALLOWED_HOSTS localhost,127.0.0.1 --type=array
```

### Get Environment Variables
```bash
envcli get <key>
```

### List All Environment Variables
```bash
envcli list
```

### Delete Environment Variables
```bash
envcli delete <key>
```

## Storage

Environment variables are stored in a `.env.json` file in your project directory:

```json
{
  "API_URL": "https://api.example.com",
  "PORT": 3000,
  "DEBUG": true,
  "ALLOWED_HOSTS": ["localhost", "127.0.0.1"]
}
```

## Support

- GitHub Issues: [Report a bug](https://github.com/MarenTech/envcli/issues)
- Documentation: [Wiki](https://github.com/MarenTech/envcli/readme.md)

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## Author

Maren Tech
- GitHub: [@maren](https://github.com/MarenTech)

