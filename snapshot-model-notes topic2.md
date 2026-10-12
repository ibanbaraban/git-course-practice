1.git capture the complete state of project at time when diff based store line by line changes

2.Blob-byte of the content

&#x20; Tree-snap of directory. have filenames and foldernames indicate blobs and other trees which belong to them 

&#x20; Commit-snap of the whole project by the time point to rootfolder(one tree) point to parent commit save  metadata: author name, email, time

3.if you do some changes hash(fixed length fingerprint) save it immediately but only if they produce identical hash

