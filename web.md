
# _api/web

- REST URL - _api/web 
- Script Name - SP.Web 
- CSOM Name - Microsoft.SharePoint.Client.Web
- Server side name - T:Microsoft.SharePoint.SPWeb 
- Base Type="Microsoft.SharePoint.Client.SecurableObject" 
- RESTful Patch Update Method - Update 
- RESTful Put Update Method - Update
- RESTful Delete Method - DeleteObject

## Methods

| Method       | Return Type  |Description|
|:---------------|:--------|:----------|
|[ApplyWebTemplate](#) | None ||
|[EnsureUser](#) | [User](user.md) ||
|[GetChanges](#) | [ChangeCollection](ChangeCollection.md) | |
|[GetList](#) | [List](list.md) | |
|[RemoveSupportedUILanguage](#) | None | |

## Properties
| Property	   | Type	| Get   | Set  | Description|
|:---------------|:--------|:----------|:--------|:----------|
|aboutMe|String| X | X | |
|accountEnabled|Boolean| X | X | |


## Relationships

| Relationship | Type	|Url|
|:---------------|:--------|:----------|
|ContentTypes|[ContentTypeCollection](ContentTypeCollection.md)| _api/web/ContentTypes |
|CurrentUser|[User](user.md)| _api/web/CurrentUser |
|Lists|[ListTemplateCollection](ListTemplateCollection.md)| _api/web/Lists |
|Webs|[WebCollection](WebCollection.md)| _api/web/Webs |


## JSON representation

Here is a JSON representation of the resource

```json
{
    "__metadata": {
      "id": "/_api/Web",
      "uri": "/_api/Web",
      "type": "SP.Web"
    },
    "FirstUniqueAncestorSecurableObject": {
      "__deferred": {
        "uri": "/_api/Web/FirstUniqueAncestorSecurableObject"
      }
    },
    "RoleAssignments": {
      "__deferred": {
        "uri": "/_api/Web/RoleAssignments"
      }
    },
    "Alerts": {
      "__deferred": {
        "uri": "/_api/Web/Alerts"
      }
    },
    "AllProperties": {
      "__deferred": {
        "uri": "/_api/Web/AllProperties"
      }
    },
    "AppTiles": {
      "__deferred": {
        "uri": "/_api/Web/AppTiles"
      }
    },
    "AssociatedMemberGroup": {
      "__deferred": {
        "uri": "/_api/Web/AssociatedMemberGroup"
      }
    },
    "AssociatedOwnerGroup": {
      "__deferred": {
        "uri": "/_api/Web/AssociatedOwnerGroup"
      }
    },
    "AssociatedVisitorGroup": {
      "__deferred": {
        "uri": "/_api/Web/AssociatedVisitorGroup"
      }
    },
    "Author": {
      "__deferred": {
        "uri": "/_api/Web/Author"
      }
    },
    "AvailableContentTypes": {
      "__deferred": {
        "uri": "/_api/Web/AvailableContentTypes"
      }
    },
    "AvailableFields": {
      "__deferred": {
        "uri": "/_api/Web/AvailableFields"
      }
    },
    "ClientWebParts": {
      "__deferred": {
        "uri": "/_api/Web/ClientWebParts"
      }
    },
    "ContentTypes": {
      "__deferred": {
        "uri": "/_api/Web/ContentTypes"
      }
    },
    "CurrentUser": {
      "__deferred": {
        "uri": "/_api/Web/CurrentUser"
      }
    },
    "DataLeakagePreventionStatusInfo": {
      "__deferred": {
        "uri": "/_api/Web/DataLeakagePreventionStatusInfo"
      }
    },
    "DescriptionResource": {
      "__deferred": {
        "uri": "/_api/Web/DescriptionResource"
      }
    },
    "EventReceivers": {
      "__deferred": {
        "uri": "/_api/Web/EventReceivers"
      }
    },
    "Features": {
      "__deferred": {
        "uri": "/_api/Web/Features"
      }
    },
    "Fields": {
      "__deferred": {
        "uri": "/_api/Web/Fields"
      }
    },
    "Folders": {
      "__deferred": {
        "uri": "/_api/Web/Folders"
      }
    },
    "Lists": {
      "__deferred": {
        "uri": "/_api/Web/Lists"
      }
    },
    "ListTemplates": {
      "__deferred": {
        "uri": "/_api/Web/ListTemplates"
      }
    },
    "Navigation": {
      "__deferred": {
        "uri": "/_api/Web/Navigation"
      }
    },
    "ParentWeb": {
      "__deferred": {
        "uri": "/_api/Web/ParentWeb"
      }
    },
    "PushNotificationSubscribers": {
      "__deferred": {
        "uri": "/_api/Web/PushNotificationSubscribers"
      }
    },
    "RecycleBin": {
      "__deferred": {
        "uri": "/_api/Web/RecycleBin"
      }
    },
    "RegionalSettings": {
      "__deferred": {
        "uri": "/_api/Web/RegionalSettings"
      }
    },
    "RoleDefinitions": {
      "__deferred": {
        "uri": "/_api/Web/RoleDefinitions"
      }
    },
    "RootFolder": {
      "__deferred": {
        "uri": "/_api/Web/RootFolder"
      }
    },
    "SiteGroups": {
      "__deferred": {
        "uri": "/_api/Web/SiteGroups"
      }
    },
    "SiteUserInfoList": {
      "__deferred": {
        "uri": "/_api/Web/SiteUserInfoList"
      }
    },
    "SiteUsers": {
      "__deferred": {
        "uri": "/_api/Web/SiteUsers"
      }
    },
    "ThemeInfo": {
      "__deferred": {
        "uri": "/_api/Web/ThemeInfo"
      }
    },
    "TitleResource": {
      "__deferred": {
        "uri": "/_api/Web/TitleResource"
      }
    },
    "UserCustomActions": {
      "__deferred": {
        "uri": "/_api/Web/UserCustomActions"
      }
    },
    "Webs": {
      "__deferred": {
        "uri": "/_api/Web/Webs"
      }
    },
    "WebInfos": {
      "__deferred": {
        "uri": "/_api/Web/WebInfos"
      }
    },
    "WorkflowAssociations": {
      "__deferred": {
        "uri": "/_api/Web/WorkflowAssociations"
      }
    },
    "WorkflowTemplates": {
      "__deferred": {
        "uri": "/_api/Web/WorkflowTemplates"
      }
    },
    "AllowRssFeeds": true,
    "AlternateCssUrl": "",
    "AppInstanceId": "00000000-0000-0000-0000-000000000000",
    "Configuration": 0,
    "Created": "2015-02-05T10:17:16",
    "CurrentChangeToken": {
      "__metadata": {
        "type": "SP.ChangeToken"
      },
      "StringValue": "1;2;cf1a6e66-1f70-4758-bffa-fec7fdad6eba;636232770638070000;17756360"
    },
    "CustomMasterUrl": "/teams/O365DevPnP/_catalogs/masterpage/seattle.master",
    "Description": "It's freaking patterns and in practices babe!",
    "DesignPackageId": "00000000-0000-0000-0000-000000000000",
    "DocumentLibraryCalloutOfficeWebAppPreviewersDisabled": false,
    "EnableMinimalDownload": true,
    "Id": "cf1a6e66-1f70-4758-bffa-fec7fdad6eba",
    "IsMultilingual": false,
    "Language": 1033,
    "LastItemModifiedDate": "2017-02-21T12:10:21Z",
    "LastItemUserModifiedDate": "2017-02-21T11:26:47Z",
    "MasterUrl": "/teams/O365DevPnP/_catalogs/masterpage/seattle.master",
    "NoCrawl": false,
    "OverwriteTranslationsOnChange": false,
    "ResourcePath": {
      "__metadata": {
        "type": "SP.ResourcePath"
      },
      "DecodedUrl": ""
    },
    "QuickLaunchEnabled": true,
    "RecycleBinEnabled": true,
    "ServerRelativeUrl": "/teams/O365DevPnP",
    "SiteLogoUrl": "/teams/O365DevPnP/SiteAssets/PnP.png",
    "SyndicationEnabled": true,
    "Title": "Office 365 Developer Patterns and Practices",
    "TreeViewEnabled": false,
    "UIVersion": 15,
    "UIVersionConfigurationEnabled": false,
    "Url": "",
    "WebTemplate": "STS"
  }
```