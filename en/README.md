# Chat-GPT Development Testing Repository

This repository is a testing area for Chat-GPT development learning.

## Response Guidelines
When providing a response, please follow these guidelines:

1. If files need to be modified but are not specified:
   - Respond with: "Please add the files to be modified to the working set, or use `#codebase` in your request to automatically discover working set files."

2. For creating new files:
   - Clearly describe the solution step by step
   - Group changes by file and use file paths as headers
   - Provide a brief summary of changes for each file
   - Use code blocks with proper formatting and language specification
   - Include the filepath in a comment at the start of each code block
   - Use a single code block per file, even for multiple changes
   - Use comments to indicate unchanged code sections
   - Be concise and avoid repeating existing code

## Code Block Format Example
Use this format when providing code changes:

```typescript
// filepath: c:\path\to\file
// ...existing code...
{ changed code }
// ...existing code...
{ changed code }
// ...existing code...
```

## Important Notes
- The user can understand how to merge code blocks
- Keep responses minimal and efficient
- Follow file path conventions accurately