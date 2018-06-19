# Mood Metrics Graphcool

This repository is a definition for legacy Graphcool backend

## Instructions
1. Create an account at <http://graph.cool>
2. Install graphcool CLI via npm: npm i -g graphcool@0.4 (it is important that you install the version 0.4, because this is a legacy project)
3. Create an empty directory and initialize a new graphcool project (graphcool init)
4. Replace the content of project.graphcool file that was created with the content of this file from this repository, keeping the project id (the first line).
5. graphcool push, now the scema should be successfully pushed
6. Go to the created project at <http://console.graph.cool/> and enable Anonymous Auth under Integrations tab.
7. Now the backend is ready to use with [mood-metrics-expo](https://github.com/d-lowl/mood-metrics-expo), the URI is under Endpoints - Simple in the console.
