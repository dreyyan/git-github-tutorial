# Version Control

## What Is Version Control?
Version control is a system that records changes to a file or set of files over time, enabling you to track, manage, and revert to specific versions as needed. It is widely used in software development to maintain a history of project changes, facilitate collaboration, and ensure project integrity.

- **Purpose**: Tracks modifications, supports collaboration, and allows recovery of previous file versions.
- **Use Cases**: Software development, documentation, and any project requiring change tracking.

## Benefits of Version Control
Version control systems (VCS) provide several advantages that streamline project management:

- **Change Tracking**: Maintains a detailed history of changes, including who made them and when.
- **Collaboration**: Enables multiple contributors to work simultaneously without overwriting each other's changes.
- **Backup and Recovery**: Allows reverting to previous versions in case of errors or unwanted changes.
- **Experimentation**: Supports creating branches to test new ideas without affecting the main project.
- **Auditability**: Provides a clear record of project evolution for accountability and debugging.

## Types of Version Control Systems
There are three main types of version control systems:

1. **Local Version Control Systems**  
   - Store changes on a single computer, typically using simple file copying or database-like systems.  
   - Example: RCS (Revision Control System).  
   - Limitations: No collaboration, risk of data loss if the local system fails.

2. **Centralized Version Control Systems (CVCS)**  
   - Use a central server to store all versions of files, with clients checking out files to work on.  
   - Examples: Subversion (SVN), Perforce.  
   - Advantages: Simplified collaboration, single source of truth.  
   - Disadvantages: Single point of failure, requires constant server connection.

3. **Distributed Version Control Systems (DVCS)**  
   - Each user has a complete copy of the repository, including its full history.  
   - Examples: Git, Mercurial.  
   - Advantages: Robust against server failures, supports offline work, and enhances collaboration through flexible workflows.  
   - Why Git?: Git is the most popular DVCS due to its speed, branching model, and widespread adoption.

This section provides the foundation for understanding version control, preparing you to dive into Git-specific concepts in the next sections.