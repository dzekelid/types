---
swagger: "2.0"
x-collection-name: DigitalOcean
x-complete: 0
info:
  title: Digital Ocean Create a new Key
  description: "To add a new SSH public key to your DigitalOcean account, send a POST
    request to /v2/account/keys. Set the \"name\" attribute to the name you wish to
    use and the \"public_key\" attribute to a string of the full public key you are
    adding.\n\nThe response body will be a JSON object with a key set to ssh_key.
    The value will be the complete generated key object. This will have the standard
    key attributes:\n\nName\tType\tDescription\nid\tinteger\tThis is a unique identification
    number for the key. This can be used to reference a specific SSH key when you
    wish to embed a key into a Droplet.\nfingerprint\tstring\tThis attribute contains
    the fingerprint value that is generated from the public key. This is a unique
    identifier that will differentiate it from other keys using a format that SSH
    recognizes.\npublic_key\tstring\tThis attribute contains the entire public key
    string that was uploaded. This is what is embedded into the root user's authorized_keys
    file if you choose to include this SSH key during Droplet creation.\nname\tstring\tThis
    is the human-readable display name for the given SSH key. This is used to easily
    identify the SSH keys when they are displayed."
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/keys:
    post:
      summary: Create a new Key
      description: "To add a new SSH public key to your DigitalOcean account, send
        a POST request to /v2/account/keys. Set the \"name\" attribute to the name
        you wish to use and the \"public_key\" attribute to a string of the full public
        key you are adding.\n\nThe response body will be a JSON object with a key
        set to ssh_key. The value will be the complete generated key object. This
        will have the standard key attributes:\n\nName\tType\tDescription\nid\tinteger\tThis
        is a unique identification number for the key. This can be used to reference
        a specific SSH key when you wish to embed a key into a Droplet.\nfingerprint\tstring\tThis
        attribute contains the fingerprint value that is generated from the public
        key. This is a unique identifier that will differentiate it from other keys
        using a format that SSH recognizes.\npublic_key\tstring\tThis attribute contains
        the entire public key string that was uploaded. This is what is embedded into
        the root user's authorized_keys file if you choose to include this SSH key
        during Droplet creation.\nname\tstring\tThis is the human-readable display
        name for the given SSH key. This is used to easily identify the SSH keys when
        they are displayed."
      operationId: AccountKeysPost
      x-api-path-slug: accountkeys-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - New
      - Key
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---