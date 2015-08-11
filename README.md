# jqm-tree
jqm-tree is a jquery mobile tree plugin
jqm-tree 是一个jquery mobile的树形插件

example(使用说明)
$("#tree").jqmtree({
        title : 'Items',
        collapsed: false,
        data: [
            { "id": 1, "title": "item1" },
            { "id": 2, "title": "item1_1", "pid":1 },
            { "id": 3, "title": "item1_2", "pid": 1 },
            { "id": 4, "title": "item2", "pid": 0 },
            { "id": 5, "title": "item3", "pid": 0 },
            { "id": 6, "title": "item1_2_1", "pid": 3 }
        ]
});
