<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LinkedIn Cringe Filter - Chrome Extension</title>
</head>
<body>
    <h1>LinkedIn Cringe Filter - Chrome Extension</h1>
    <p>The LinkedIn Cringe Filter is a Chrome extension designed for educational purposes only. It filters LinkedIn posts, translating and refining cringe-worthy content into simpler, more professional language. This extension helps make LinkedIn a more polished experience by streamlining overly casual or awkward posts into something more appropriate for a professional network.</p>

    <h2>Installation</h2>
    <h3>1. Download the Extension</h3>
    <p>This extension is for manual installation and is intended for educational use only.</p>
    <p>1. Download the extension files (ZIP) or clone the repository to your local machine.</p>

    <h3>2. Manual Installation (For Developer Mode)</h3>
    <p>Follow these steps to install the extension manually:</p>
    <ol>
        <li>Open <strong>Google Chrome</strong> and navigate to <code>chrome://extensions</code>.</li>
        <li>Enable <strong>Developer Mode</strong> by toggling the switch in the top right corner.</li>
        <li>Click <strong>Load unpacked</strong>, then select the folder where the extension files are saved.</li>
        <li>The extension will be installed and active.</li>
    </ol>

    <h2>Configuration</h2>
    <p>Before using the extension, you'll need to add your OpenAI API key for the content filtering to work.</p>
    <ol>
        <li>Open the extension's folder and find the <strong>config.json</strong> file.</li>
        <li>Open <strong>config.json</strong> in a text editor.</li>
        <li>Replace the placeholder <code>"your_openai_api_key_here"</code> with your actual OpenAI API key.</li>
        <li>Save the file.</li>
    </ol>
    <p>The extension will now be able to interact with OpenAI’s API for content refinement.</p>

    <h2>Usage</h2>
    <h3>1. Activate the Extension</h3>
    <p>Once the extension is installed, it will be visible in the toolbar of your Chrome browser.</p>
    <p>Click on the extension icon to enable it. The extension will automatically detect posts on LinkedIn and refine any that are considered "cringe-worthy" (overly casual or awkward language).</p>

    <h3>2. How It Works</h3>
    <p>When you browse LinkedIn, the extension scans the posts. If a post is deemed cringe-worthy, the extension automatically translates and refines it into simpler, more professional language. The refined version will be displayed in place of the original post.</p>

    <h2>Troubleshooting</h2>
    <p><strong>The extension isn't working properly:</strong></p>
    <ul>
        <li>Ensure that you have the latest version of Google Chrome installed.</li>
        <li>Make sure the extension is enabled in your Chrome extensions settings (<code>chrome://extensions</code>).</li>
        <li>Ensure your OpenAI key is correctly configured in the <strong>config.json</strong> file.</li>
        <li>Try restarting Chrome to refresh the extension.</li>
    </ul>

    <p><strong>I want to remove the extension:</strong></p>
    <ul>
        <li>Go to <code>chrome://extensions</code>.</li>
        <li>Find the LinkedIn Cringe Filter extension and click <strong>Remove</strong>.</li>
    </ul>
</body>
</html>
