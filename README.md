<!DOCTYPE html>

<head>
    <title>Mars</title>
</head>

<body>
    <table align="center" border="1" height="450px" width="300px" cellspacing="0">
        <tr align="center">
            <td width="60" colspan="6">信息统计表</td>
        </tr>
        <tr align="center">
            <td width="50">姓名：</td>
            <td width="50" colspan="5">
                <input type="text">
            </td>
        </tr>
        <tr align="center">
            <td width="50">年龄：</td>
            <td width="50" colspan="5">
                <input type="text">
            </td>
        </tr>
        <tr align="center">
            <td width="60">性别：</td>
            <td width="60" colspan="5">
                <label><input type="radio" name="sex" value="1">男</label>
                <label><input type="radio" name="sex" value="0">女</label>
            </td>
        </tr>
        <tr align="center">
            <td width="60">爱好：</td>
            <td width="60" colspan="5">
                <label><input type="checkbox" name="like" value="0">旅游</label>
                <label><input type="checkbox" name="like" value="1">登山</label>
                <label><input type="checkbox" name="like" value="2">健身</label>
                <label><input type="checkbox" name="like" value="3">上网</label>
                <label><input type="checkbox" name="like" value="4">游泳</label>
            </td>
        </tr>
        <tr align="center">
            <td width="60">学历：</td>
            <td width="60" colspan="5">
                <select name="degree">
                    <option value="">--请选择--</option>
                    <option value="1">专科</option>
                    <option value="2">本科</option>
                    <option value="3">硕士</option>
                    <option value="4">博士及以上</option>
                </select>
            </td>
        </tr>
        <tr align="center">
            <td width="60">自我介绍：</td>
            <td width="60" colspan="5">
                <textarea name="comment" cols="30" rows="5" style="resize:none;">自我介绍：</textarea>
            </td>
        </tr>
        <tr align="center">
            <td width="60"></td>
            <td width="60" colspan="5">
                <input type="submit" value="提交">
                &nbsp;&nbsp;&nbsp;
                <input type="reset" value="重置">
                &nbsp;&nbsp;&nbsp;
                <input type="button" value="返回">
            </td>
        </tr>
    </table>
</body>

</html>
