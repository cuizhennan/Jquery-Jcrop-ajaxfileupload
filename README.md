Jcrop-ajaxfileupload
====================

Jcrop+ajaxfileupload+jquery

jsp +javaScript

jsp page:
<!-- 头像上传  start -->
		<div class="uploadImage" id="uploadImage">
			<div class="imgTitle">
				<label>头像上传</label>
			</div>
			<div class="uploadTools">
					<span class="uploadButton">
						<label for="uploadHead" class="labelButton">请选择照片</label>
						<s:file name="uploadImg" onchange="viewImg(this)" id="uploadHead" cssClass="fileButton"/>
						<s:hidden name="imgName" id="imgName"/>
							<s:hidden name="x" id="x"/>
							<s:hidden name="y" id="y"/>
							<s:hidden name="w" id="w"/>
							<s:hidden name="h" id="h"/>
					</span>
					<label class="loading">
						<img alt="" id="loading" src="images/onLoad.gif">
					</label>
					<span class="uploadMessWarn"></span>
					<span class="OkButton">
						<label>确定</label>
					</span>
					<span class="cancalButton">
						<label>取消</label>
					</span>
			</div>
			<div class="uploadView">
				<div class="uploadFont">
					<label>仅支持JPG 文件小于5M。</label>
				</div>
				<div class="upView" id="upView" style="float:left;">
				 	<img alt="" id="sourceImg" src="images/headImgs/default1.jpg" style="float: left;">
				</div>
			</div>
			<div class="leftView">
				<div class="separateBar"></div>
				<div class="rightMaxFont"><label>84×84</label></div>
				<div class="rightMax">
					<img alt="" id="rightMaxImg" src="images/headImgs/default1.jpg" style="float: left;">
				</div>	
				<div class="rightFirstFont"><label>50×50</label></div>
				<div class="rightFirst">
					<img alt="" id="rightFirstImg" src="images/headImgs/default1.jpg" style="float: left;">
				</div>
				<div class="rightMinFont"><label>45×45</label></div>
				<div class="rightMin">
					<img alt="" id="rightMinImg" src="images/headImgs/default1.jpg" style="float: left;">
				</div>
			</div>
		</div>





