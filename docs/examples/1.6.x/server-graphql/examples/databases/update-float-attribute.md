mutation {
    databasesUpdateFloatAttribute(
        databaseId: "<DATABASE_ID>",
        collectionId: "<COLLECTION_ID>",
        key: "",
        required: false,
        min: 0,
        max: 0,
        default: 0,
        newKey: ""
    ) {
        key
        type
        status
        error
        required
        array
        min
        max
        default
    }
}
