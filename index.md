---
layout: default
---

<style> .footer-t, .banner-wrapper { display: none; } .news-wrapper:hover img { transform: translate(0%, 0%) scale(0.8); } .news-wrapper .img-holder { text-align: center; height: 100px; padding-top: 5px; } .img-holder img { height: 100%; } .caption { text-align: center; color: black; max-height: 22px; } .news-wrapper { border: 2px solid #132c6c; background-color: #f7f7f8; border-radius: 10px; padding-bottom: 15px; } .banner { min-height: 50px; background-image: 0; }</style>
<div id="root--"></div>

<script type="text/javascript">
function app(text, url, image) { this.text = text; this.url = url; this.image = image; }
function addItem(item, index) {
	var element = document.createElement('div');
	element.innerHTML = '<a target="_blank" href="'+item.url+'">\
		<article class="col-sm-3">\
			<div class="thumbnail news-wrapper">\
				<div class="img-holder">\
					<img src="'+item.image+'">\
				</div>\
				<div class="caption">\
					'+item.text+'</>\
		</article>\
	</a>';
	document.getElementById("root--").appendChild(element);
}

var items = [
	new app("Google Search", "http://www.google.com.au", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/google.png"),
	new app("Student Gmail", "https://mail.google.com/a/student.ddcs.qld.edu.au", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/gmail.png"),
	new app("Office 365", "http://portal.office365.com/", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/o365.png"),
	new app("PaperCut", "http://papercut.ddcs.qld.edu.au", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/papercut.png"),
	new app("OnGuard", "http://www.1300acepro.com/OnGuardACEPro2014/content/login.asp?schoolKey=darlingdownscs.qld", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/onguard.png"),
	new app("Student Login", "http://student.wordflyers.com/login", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/wf.png"),
	new app("Blocked Site Overrides", "https://lesson.localnetwork.zone/", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/cyberhound2.png"),
	new app("School Calendar", "https://www.ddcs.qld.edu.au/parent-lounge/calendar", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/calendar.png"),
	new app("ACER Testing", "https://oars.acer.edu.au/darling-downs-christian-school", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/acer.png"),
	new app("Student Login", "https://www.typing.com/student/login/", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/typing.com.png"),
	new app("Parent Interviews", "https://www.schoolinterviews.com.au/", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/interviews.png"),
	new app("Tuckshop", "https://www.ouronlinecanteen.com.au/", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/quickcliq.png"),
	new app("ICT Handbook", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/documents/Student-Parent-Handbook-ICT-Terms-Conditions-2017.pdf", "https://s3-ap-southeast-2.amazonaws.com/digistorm-websites/ddcs-au-qld-140-website/content/portal-icons/notebook.png"),


];
items.forEach(addItem);
</script>


<div>
<p>
<br>
</p>
</div>

<div>
<h2>Verse of the day</h2>
<script src="https://static6-a.akamaihd.net/votd/votd.write.callback.js"></script>
<script src="https://www.biblegateway.com/votd/get/?format=json&version=NIV&callback=BG.votdWriteCallback"></script>
<!-- alternative for no javascript -->
<noscript>
<iframe framespacing="0" frameborder="no" src="https://www.biblegateway.com/votd/get/?format=html&version=NIV">View Verse of the Day</iframe> 
</noscript>
<br>
</div>