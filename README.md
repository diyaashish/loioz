This is the naive approahch to the issue. wherein i added radio buttons for status and checkboxes for attributes. after the meeting that took place on 28/06/2023 the approach has changed directions. 
Thus changes made previously are saved here instead of the diyaashish-branch. 

**status of invitees:**

<div class="participantStatus">
  <label><input type="radio" name="status" value="unresponded"> 未回答</label>
  <label><input type="radio" name="status" value="participation"> 参加</label>
  <label><input type="radio" name="status" value="non-participation"> 不参加</label>
</div>

This code adds radio buttons for the status of invitees, including "未回答" (unresponded), "参加" (participation), and "不参加" (non-participation).

**attributes of invitees:**

<div class="inviteeAttributes">
  <label><input type="checkbox" name="optionalParticipation" value="optional"> 志願参加</label>
  <label><input type="checkbox" name="informationSharing" value="sharing"> 情報共有</label>
</div>

This code adds checkboxes for the attributes of invitees, including "志願参加" (optional participation) and "情報共有" (information sharing).
