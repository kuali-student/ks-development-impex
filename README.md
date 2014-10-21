# Kuali Student Impex

Please refer to [kuali-student.github.io](https://kuali-student.github.io) for information on how to build the project using this project.

For development going forward this is the intended location for the manual impex process created .mpx files to be committed into; code changes should be contributed as pull requests against the [ks-development](https://github.com/kuali-student/ks-development) repository.

## Purpose of this repository

Impex files take up a tremendous amount of space over time.  Two years worth of .mpx files accounted for over 50% of the entire Kuali Student Repository when converted from Subversion into Git.

The purpose of this repository is to keep that space growth out of the main code repository.  

The intent was that when a pull request was merged into master there would be a build tag created in both the ks-development repository and this repository.

