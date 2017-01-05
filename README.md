# OpenSubtitlesHash.swift
Swift 3 class for generating file hash compatible with opensubtitles.org's API. More information about the OpenSubtitles API at [http://trac.opensubtitles.org/projects/opensubtitles](http://trac.opensubtitles.org/projects/opensubtitles).

## Usage example
```swift
let videoUrl = Bundle.main.url(forResource: "dummy5", withExtension: "rar")
let videoHash = OpenSubtitlesHash.hashFor(videoUrl!)
debugPrint("File hash: \(videoHash.fileHash)\nFile size: \(videoHash.fileSize)")
```

## Installation
Manual installation by including OpenSubtitlesHash.swift in project.