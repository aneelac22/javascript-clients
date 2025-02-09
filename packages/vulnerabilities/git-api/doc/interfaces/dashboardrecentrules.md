[@redhat-cloud-services/vulnerabilities-client](../README.md) › [Globals](../globals.md) › [DashboardRecentRules](dashboardrecentrules.md)

# Interface: DashboardRecentRules

Security rule.

**`export`** 

**`interface`** DashboardRecentRules

## Hierarchy

* **DashboardRecentRules**

## Index

### Properties

* [associated_cves](dashboardrecentrules.md#optional-associated_cves)
* [description](dashboardrecentrules.md#optional-description)
* [id](dashboardrecentrules.md#optional-id)
* [name](dashboardrecentrules.md#optional-name)
* [node_id](dashboardrecentrules.md#optional-node_id)
* [public_date](dashboardrecentrules.md#optional-public_date)
* [severity](dashboardrecentrules.md#optional-severity)
* [systems_affected](dashboardrecentrules.md#optional-systems_affected)

## Properties

### `Optional` associated_cves

• **associated_cves**? : *Array‹string›*

*Defined in [packages/vulnerabilities/git-api/api.ts:609](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L609)*

List of CVEs associated with the security rule.

**`memberof`** DashboardRecentRules

___

### `Optional` description

• **description**? : *string*

*Defined in [packages/vulnerabilities/git-api/api.ts:615](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L615)*

Description of the issue related with the security rule.

**`memberof`** DashboardRecentRules

___

### `Optional` id

• **id**? : *string*

*Defined in [packages/vulnerabilities/git-api/api.ts:621](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L621)*

ID of the security rule.

**`memberof`** DashboardRecentRules

___

### `Optional` name

• **name**? : *string*

*Defined in [packages/vulnerabilities/git-api/api.ts:627](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L627)*

Name of the security rule.

**`memberof`** DashboardRecentRules

___

### `Optional` node_id

• **node_id**? : *number | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:633](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L633)*

Node id of access.redhat.com/node/_* article.

**`memberof`** DashboardRecentRules

___

### `Optional` public_date

• **public_date**? : *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:639](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L639)*

String representation of ISO-8601 formatted date of release of the security rule.

**`memberof`** DashboardRecentRules

___

### `Optional` severity

• **severity**? : *number*

*Defined in [packages/vulnerabilities/git-api/api.ts:645](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L645)*

Number representation of the security rule severity.

**`memberof`** DashboardRecentRules

___

### `Optional` systems_affected

• **systems_affected**? : *number*

*Defined in [packages/vulnerabilities/git-api/api.ts:651](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L651)*

Number of systems triggering the security rule.

**`memberof`** DashboardRecentRules
