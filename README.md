### table-template
```html
  <style>
        .left-table-new {
            float: left;
            width: 45%;
            font-size: 14px;
            border: 1px solid #ccc;
        }
        .left-table-new .tab {
            cursor: pointer;
        }
        .left-table-new .tab div {
            float: left;
            padding: 10px;
            font-weight: bold;
            font-size: 14px;
        }
        .left-table-new .tab .active {
            border-bottom: 4px solid #2b7df9
        }
        .left-table-new .bg-grey {
            background: #EDF2F6;
        }
        .left-table-new table {
            border-collapse: collapse;
        }
        .left-table-new .border-bottom {
            border-bottom: 2px solid #fff;
        }
        .left-table-new .border-bottom-grey {
            border-bottom: 1px solid #ccc;
        }
        .left-table-new .border-bottom-grey:last-of-type {
            border-bottom: 0 none;
        }
        .left-table-new .border-right-left {
            border-right: 2px solid #fff;
            border-left: 2px solid #fff;
        }
        .left-table-new .border-right {
            border-right: 2px solid #fff;
        }
        .left-table-new .border-left {
            border-left: 2px solid #fff;
        }
        .left-table-new .table {
            display: none;
        }
        .left-table-new .table th {
            font-weight: normal;
        }
        .left-table-new .table.active {
            display: block;
        }
        .left-table-new .h32 {
            height: 32px;
            text-align: center;
        }
    </style>
    <div class="left-table-new">
        <div class="tab" id="leftTableNewTab">
            <div class="active" tableIndex='left-table-new-table-1'>原材料</div>
            <div tableIndex='left-table-new-table-2'>人工</div>
            <div tableIndex='left-table-new-table-3'>成本价格</div>
        </div>
        <div class="table left-table-new-table-1 active">
            <table width="100%">
                    <tr class="bg-grey table-header">
                        <th >序号</th>
                        <th width='20%' class="border-right-left">名称</th>
                        <th >规格</th>
                        <th  class="border-right-left">单位</th>
                        <th class="border-right" >构成量</th>
                        <th colspan=3>
                            <table  cellspacing="0" cellpadding="5px" width="100%">
                            <tr>
                                <td class="border-bottom" colspan=3 align="center">价格</td>
                            </tr>
                            <tr>
                                <td align="center" width="33.33%">本期</td>
                                <td align="center" width="33.33%" class="border-right-left">上期</td>
                                <td align="center" width="33.33%">浮动(%)</td>
                            </tr>
                            </table>
                            
                        </th>
                        <th class="border-left">说明</th>
                    </tr>
                    <tr class="border-bottom-grey h32">
                        <td>1</td>
                        <td>普通硅酸盐水泥（国产）</td>
                        <td>42.5（R）散装</td>
                        <td>t</td>
                        <td>450</td>
                        <td>134.11111</td>
                        <td>139.12121</td>
                        <td>-10.22</td>
                        <td>9</td>
                    </tr>
                    <tr class="border-bottom-grey h32">
                        <td>1</td>
                        <td>2</td>
                        <td>3</td>
                        <td>4</td>
                        <td>5</td>
                        <td>6</td>
                        <td>7</td>
                        <td>8</td>
                        <td>9</td>
                    </tr>
            </table>          
        </div>
        <div class="table left-table-new-table-2">
            <table width="100%">
                    <tr class="bg-grey table-header">
                        <th >序号</th>
                        <th width='20%' class="border-right-left">名称</th>
                        <th  class="border-right-left">单位</th>
                        <th colspan=3>
                            <table  cellspacing="0" cellpadding="5px" width="100%">
                            <tr>
                                <td class="border-bottom" colspan=3 align="center">价格</td>
                            </tr>
                            <tr>
                                <td align="center" width="33.33%">本期</td>
                                <td align="center" width="33.33%" class="border-right-left">上期</td>
                                <td align="center" width="33.33%">浮动(%)</td>
                            </tr>
                            </table>
                            
                        </th>
                        <th class="border-left">说明</th>
                    </tr>
                    <tr class="border-bottom-grey h32">
                        <td>1</td>
                        <td>2</td>
                        <td>3</td>
                        <td>4</td>
                        <td>5</td>
                        <td>6</td>
                        <td>7</td>
                    </tr>
                    <tr class="border-bottom-grey h32">
                        <td>1</td>
                        <td>2</td>
                        <td>3</td>
                        <td>4</td>
                        <td>5</td>
                        <td>6</td>
                        <td>7</td>
                    </tr>
            </table>          
        </div>
        <div class="table left-table-new-table-3">
            <table width="100%">
                    <tr class="bg-grey table-header">
                        <th colspan=3>
                            <table  cellspacing="0" cellpadding="5px" width="100%">
                            <tr>
                                <td class="border-bottom" colspan=3 align="center">综合费用</td>
                            </tr>
                            <tr>
                                <td align="center" width="33.33%">本期</td>
                                <td align="center" width="33.33%" class="border-right-left">上期</td>
                                <td align="center" width="33.33%">浮动(%)</td>
                            </tr>
                            </table>
                        </th>
                        <th colspan=3 class="border-left">
                            <table  cellspacing="0" cellpadding="5px" width="100%">
                            <tr>
                                <td class="border-bottom" colspan=3 align="center">原材料价格</td>
                            </tr>
                            <tr>
                                <td align="center" width="33.33%">本期</td>
                                <td align="center" width="33.33%" class="border-right-left">上期</td>
                                <td align="center" width="33.33%">浮动(%)</td>
                            </tr>
                            </table>
                        </th>
                        <th class="border-left">说明</th>
                    </tr>
                    <tr class="border-bottom-grey h32">
                        <td>1</td>
                        <td>2</td>
                        <td>3</td>
                        <td>4</td>
                        <td>5</td>
                        <td>6</td>
                        <td>7</td>
                    </tr>
                    <tr class="border-bottom-grey h32">
                        <td>1</td>
                        <td>2</td>
                        <td>3</td>
                        <td>4</td>
                        <td>5</td>
                        <td>6</td>
                        <td>7</td>
                    </tr>
            </table>          
        </div>
    </div>
    <script>
        $(function() {
            $('#leftTableNewTab').click(function(e){
                $('#leftTableNewTab div').removeClass('active')
                $(e.target).addClass('active');
                $('.table').removeClass('active');
                $('.' + $(e.target).attr('tableIndex')).addClass('active');
            })
        });
    </script>
```
