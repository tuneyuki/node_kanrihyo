# node_kanrihyo

# モデリング

```
items : {
  name : {
    type: String,
    required: true
  },
  category: {
    cat_id: Number,
    required: true
  },
  tags: [String]
}

category = [ 'Computer', 'Stationary', 'Appliance', 'Furniture' ];

details : {
  item_id: {
    type: _id,
    required: true
  },
  price: {
    type: Number
  },
  size: {
    wdh : Number
  }
}

comments : {
  item_id: {
    type: Object_id
    required: true
  },
  owner: {
    type: String,
    required: true
  },
  comment: {
    type: String,
    required: true
  }
}
```
