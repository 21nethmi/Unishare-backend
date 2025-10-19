# Unishare-backend
Web-based note sharing and chat system developed using Java Network Programming and React.
backend/
│
├── src/
│   ├── modules/              # Module listing feature (Member 1)
│   │   ├── ModuleClient.java
│   │   └── ModuleServer.java
│   │
│   ├── upload/               # File upload feature (Member 2)
│   │   ├── FileUploadClient.java
│   │   └── FileUploadServer.java
│   │
│   ├── download/             # File download feature (Member 3)
│   │   ├── FileDownloadClient.java
│   │   └── FileDownloadServer.java
│   │
│   ├── chat/                 # Chat and notification (Member 4)
│   │   ├── ChatServer.java
│   │   ├── ChatClient.java
│   │   └── NotificationHandler.java
│   │
│   ├── log/                  # Logging system (Member 5)
│   │   ├── ActivityLogger.java
│   │   └── LogServer.java
│   │
│   └── common/               # Shared code (utilities, constants, etc.)
│       └── Utils.java
│
├── uploads/                  # where uploaded files are stored
├── logs/                     # activity log files
├── resources/                # configuration or text data
│
├── README.md
└── .gitignore

