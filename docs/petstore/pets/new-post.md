---
'position': 1
---

# Add a new Pet to the store

## Add new pet to the store inventory.

### Header Parameters

`Accept-Language` string

The language you prefer for messages. Supported values are en-AU, en-CA, en-GB, en-US

Example: en-US

### Cookie Parameters

`cookieParam` int64 — REQUIRED

Some cookie

**Request Body** — REQUIRED

**Pet object that needs to be added to the store
id int64**

Pet ID

`category` Category

Categories this pet belongs to

`id` int64

Category ID

`name` string

**Possible values:** 1 ≤ length

Category name

`sub` object

Test Sub Category

`prop1` string

Dumb Property

`name` string — REQUIRED

The name given to a pet
photoUrls url[] — REQUIRED

The list of URL to a cute photos featuring pet
`friend` (circular)

`tags` Tag[]

Tags attached to the pet

`id` int64

Tag ID
`name` string

**Possible values:** 1 ≤ length

Tag name

`status` string

**Possible values:** [available, pending, sold]

Pet status in the store
`petType` string

Type of a pet
