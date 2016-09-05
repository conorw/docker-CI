# Test app for Pluralsight course

This is a quick and dirty test node.js app cobbled together for the purposes of demonstrating a basic CI/CD workflow with Docker Hub for a Pluralsight video training course..

## Instructions for use

All of the files included in the .zip file (available to Plus subscribers) should be unzipped into a new directory.

Initializing a Git repo and making a remote of it on GitHub are explained in Module 2 of the course.

The viewer should have Git installed and have a GitHub account.

Trigger var
curl -H "Content-Type:application/json" --data '{"build":true}' -X POST https://registry.hub.docker.com/u/conorw/docker-ci/trigger/5a07e217-bc31-412f-8a5e-267784ce5b6f/