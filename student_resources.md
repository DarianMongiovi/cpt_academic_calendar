erDiagram
    STUDENT_SERVICES {
        string department PK
        string phone
        string email
        string hours
    }
    PROFESSORS {
        string name PK
        string department
        string email
    }
    LINUX {
        string distro PK
        string documentation
        string iso
    }
    COMPTIA_CCNA_CCISP {
        string cert PK
        string objectives
        string resources
    }
