# uidu-dataviews

Collection of presaved dataviews for reading your data.

## Example configuration

```yaml
# Visible to organization, localized
name:
  en: Latest donations
  it: Ultime donazioni

# Available kinds @uidu/data-views
kind: table

# Default sorters applied to this view <fieldname>:<sortDirection>
sorters:
  - createdAt:desc

# Default filters applied to this view <fieldname> <filter> <filterValue>
filters:
  - groupId is slug
  - groupId is volunteers,donors,corporates

# Fields that need to be created for this view to work
fields:
  - name:
      en:
      it:
    kind:
    options:
  - name:
      en:
      it:
    kind:
    options:
```
