This graph shows our team's collaborations with other teams and stakeholders:

```mermaid
flowchart TB
%%{init: {'theme': 'neutral', 'themeVariables': { 'fontSize': '25px'}}}%%
    classDef default fill:#fff,stroke:#1d4289,color:#1d4289,stroke-width:4px;

    dacs((Discovery and Access))

    %% Collaborators
    access(Library Access)
    alma(Alma managers)
    acq(Acquisitions)
    circulation(Circulation)
    communications(Communications)
    dlss(DLSS)
    eresources(E-resources)
    faculty(Faculty)
    finance(Finance)
    fpul(Friends of PUL)
    metadata(Metadata)
    recap(ReCAP)
    research(Research Data)
    resource(Resource Sharing)
    special(Special Collections)
    subject(Subject Librarians)


    %% Systems
    subgraph Internal systems
      alma-integrations{Alma Integrations}
      approvals{Approvals}
    end
    subgraph Public systems
      aspace{Aspace}
      catalog{Catalog}
      lockers{Lockers}
      websites{Public Facing Websites}
    end

    %% Relationships
    dacs-->alma-integrations
    dacs-->approvals
    dacs-->aspace
    dacs-->catalog
    dacs-->lockers
    dacs-->websites
    
    alma-->alma-integrations
    acq-->alma-integrations
    circulation-->alma-integrations
    finance-->alma-integrations

    special-->aspace

    alma-->catalog
    circulation--Requests-->catalog
    dlss--Figgy integration-->catalog
    eresources-->catalog
    metadata-->catalog
    resource--Requests-->catalog
    special-->catalog

    access-->lockers

    communications-->websites
    faculty--Princeton and Slavery-->websites
    fpul-->websites
    recap-->websites
    research-->websites
    special-->websites
    subject-->websites


```

