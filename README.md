# ExcelTranslator
Translates Excel cells with Azure Congitive Services

## Usage
1. Create Text Translation Cognitive Service with Azure
2. Generate API key
3. Set the key to `Const ACCOUNT_KEY` at `Translator::GetAccessToken`
4. Set target language to `sLanguageTo` in `Main::translate`
