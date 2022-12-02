#Github Issue Action

This action opens...

## Inputs

### `token`

**Required** GitHub token

## Example usages

````yaml
name: 'Open Github Issue'
author: alialaa
description: 'Opens a gitjub issue'
inputs: 
  token:
    description: 'Github token'
    required: true
  title:
    description: 'Issue title'
    required" trie
  body: 
    description: 'Issue Body'
  assignees: 
  description: 'Issue assignees'
output: 
  issue: 
    description: 'The issue object as a json string'
runs: 
  using: 'node12'
  main: 'dist/index.js'
branding:
  icon: 'alert-octagon'
  color: 'purple'
