# hermes-echo
Speech-to-Text writing editor

---
## Outline

> *The idea came to me in a dream like a phrophecy.*

The inspiration of this app comes from an old timey tradition where someone in power has to write a letter, but obviously does not do it by hand. Typically, they have transcriber writing (or typing) all their words out for them while they continuously ramble on. The goal is to have an application that can act as a transcriber - editing and writing a passage while the user speaks it outloud.

### Functional Requirements 
> Subject to change

1. User Log In
    - Application must allow users to create an account to store transcribed text

2. Speech Recognition
    - Application should be able to capture real-time audio input from the user
    - Application should transcribe spoken word to text
    - Application should allow users to start, pause, resume, and stop the transcription process

3. Transcription & Editing
    - Applicaiton should be able to correct common speech recognition errors (this will probably be done by the package)
    - Application should allow users to voice commands for punctuation (period, new paragraph, etc.)
    - Application should allow users to undo stuff manually
    - Application should allow users to manually edit the transcibed text as well

4. Text Formatting
    - Application should allow users to apply formatting options (bold, italic, underlining)
    - Application should support bullet points and numbered lists

5. Storage
    - Application should allow users to transcribed text as a document
    - Application should store a users transcribed set into a database and allow them to access it whenever

6. Voice Command-Base Editing
    - Application should be able to recognize voice commands for editing such as replacing words or deleting segments
    - Application should not confuse commands with spoken word meant to be transcibed
    - Application should allow users to customize some voice commands

7. UI and UX
    - Application should provide visual feedback when processing speech input
    - Application should display real-time word confidence scores (optional)

### Non Functional Requirements
> Subject to change

1. Application must be simplistic and intuitive for the average user
2. Application should be available often with very little downtime
3. Application must be fast and efficient when trascribing the users words and editing to ensure real-time feel
4. Application should be able to handle large text files and manage incoming users flawlessly
5. Application must be able to function under poor connection, maintaing integrity of transcribed text
6. Application must be secure with users information relating to their log in

### Pathway

1. **Phase 1**: Core Transcription (In Progress - Started: 2025-02-18)
    - *Goal 1*: Create a simple, functional transcribing tool that allows a user to stop and resume recording (Started: 2025-02-18, Finished: N/A)

1. **Phase 2**: Editing & Formatting (Not Started)
