This graph shows our team's collaborations with other teams and stakeholders:

```mermaid
graph TB
    dacs((Discovery and Access))
    dacs --- aspace-special

    dacs -- Figgy integration --- catalog-dlss
    dacs --- catalog-subject
    dacs --- catalog-metadata
    dacs --- catalog-special
    dacs --- catalog-eresource
    dacs --- catalog-patrons

    dacs --- web-subject
    dacs --- web-special
    dacs -- Princeton and Slavery --- web-faculty
    dacs --- web-patrons

    subgraph Aspace
      aspace-special((Special collections))
    end
    subgraph Catalog
      catalog-dlss((DLSS))
      catalog-special((Special collections))
      catalog-subject((Subject specialists))
      catalog-metadata((Metadata))
      catalog-eresource((E-resources team))
      catalog-patrons((Patrons))
    end
    subgraph Public facing Websites
      web-faculty((Faculty))
      web-patrons((Patrons))
      web-special((Special collections))
      web-subject((Subject librarians))
    end

```
