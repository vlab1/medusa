---
displayed_sidebar: jsClientSidebar
---

# Class: User

[internal](../modules/internal-1.md).User

Base abstract entity for all entities

## Hierarchy

- [`SoftDeletableEntity`](internal-1.SoftDeletableEntity.md)

  ↳ **`User`**

## Properties

### api\_token

• **api\_token**: `string`

#### Defined in

packages/medusa/dist/models/user.d.ts:13

___

### beforeInsert

• `Private` **beforeInsert**: `any`

#### Defined in

packages/medusa/dist/models/user.d.ts:15

___

### created\_at

• **created\_at**: `Date`

#### Inherited from

[SoftDeletableEntity](internal-1.SoftDeletableEntity.md).[created_at](internal-1.SoftDeletableEntity.md#created_at)

#### Defined in

packages/medusa/dist/interfaces/models/base-entity.d.ts:6

___

### deleted\_at

• **deleted\_at**: ``null`` \| `Date`

#### Inherited from

[SoftDeletableEntity](internal-1.SoftDeletableEntity.md).[deleted_at](internal-1.SoftDeletableEntity.md#deleted_at)

#### Defined in

packages/medusa/dist/interfaces/models/soft-deletable-entity.d.ts:3

___

### email

• **email**: `string`

#### Defined in

packages/medusa/dist/models/user.d.ts:9

___

### first\_name

• **first\_name**: `string`

#### Defined in

packages/medusa/dist/models/user.d.ts:10

___

### id

• **id**: `string`

#### Inherited from

[SoftDeletableEntity](internal-1.SoftDeletableEntity.md).[id](internal-1.SoftDeletableEntity.md#id)

#### Defined in

packages/medusa/dist/interfaces/models/base-entity.d.ts:5

___

### last\_name

• **last\_name**: `string`

#### Defined in

packages/medusa/dist/models/user.d.ts:11

___

### metadata

• **metadata**: [`Record`](../modules/internal.md#record)<`string`, `unknown`\>

#### Defined in

packages/medusa/dist/models/user.d.ts:14

___

### password\_hash

• **password\_hash**: `string`

#### Defined in

packages/medusa/dist/models/user.d.ts:12

___

### role

• **role**: [`UserRoles`](../enums/internal-1.UserRoles.md)

#### Defined in

packages/medusa/dist/models/user.d.ts:8

___

### updated\_at

• **updated\_at**: `Date`

#### Inherited from

[SoftDeletableEntity](internal-1.SoftDeletableEntity.md).[updated_at](internal-1.SoftDeletableEntity.md#updated_at)

#### Defined in

packages/medusa/dist/interfaces/models/base-entity.d.ts:7
