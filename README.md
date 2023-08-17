# Bootstrap form training
This is a training about the form elements by using Bootstrap.<br>
focus: input-group, dropdown-toggle, dropdown-menu, dropdown-item

        <div class="input-group mb-3"><!--be a container for set the elements-->
            <!--be the dropdown botton. data-bs-toggle="dropdown" needs-->
            <button class="btn btn-danger dropdown-toggle" type="button" id="button1" data-bs-toggle="dropdown">搜尋</button> 
            <!--the dropdown list-->
            <ul class="dropdown-menu"><!--class="dropdown-menu" hide the list-->
                <li><a class="dropdown-item" href="#" target="_blank">美食</a></li>
                <li><a class="dropdown-item" href="#" target="_blank">旅遊</a></li>
                <li><a class="dropdown-item" href="#" target="_blank">露營</a></li>
            </ul>
            <!--the input space-->
            <input type="text" class="form-control" placeholder="輸入要搜尋的關鍵字"><!--the order could be exchange with whole dropdown button-->
        </div>
        <label for="fruit" class="form-label">選擇你喜歡的水果</label>
            <select class="form-select form-select-lg mb-3" multiple id="fruit"><!--the width used the css to fix-->
                <option selected>選擇你喜歡的水果</option> 
                <option value="fruit1">蘋果</option>
                <option value="fruit2">香蕉</option>
                <option value="fruit3">櫻桃</option>
                <option value="fruit4">橘子</option>
                <option value="fruit5">鳳梨</option>
                <option value="fruit6">草莓</option>
            </select>
            
