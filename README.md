# Bootstrap Comments

Responsive Comment Box built with the Bootstrap 5. Comment with avatar, nested comments, comment with reply, comment section, comment template, unread comments, comment form & more.

## Basic example

HTML
```html
<div class="row d-flex justify-content-center">
  <div class="col-md-8 col-lg-6">
    <div class="card shadow-0 border" style="background-color: #f0f2f5;">
      <div class="card-body p-4">
        <div class="form-outline mb-4">
          <input
            type="text"
            id="addANote"
            class="form-control"
            placeholder="Type comment..."
          />
          <label class="form-label" for="addANote">+ Add a note</label>
        </div>

        <div class="card mb-4">
          <div class="card-body">
            <p>Type your note, and hit enter to add it</p>

            <div class="d-flex justify-content-between">
              <div class="d-flex flex-row align-items-center">
                <img
                  src="https://mdbootstrap.com/img/Photos/Avatars/img%20(4).jpg"
                  alt="avatar"
                  width="25"
                  height="25"
                />
                <p class="small mb-0 ms-2">Martha</p>
              </div>
              <div class="d-flex flex-row align-items-center">
                <p class="small text-muted mb-0">Upvote?</p>
                <i
                  class="far fa-thumbs-up mx-2 fa-xs text-black"
                  style="margin-top: -0.16rem;"
                ></i>
                <p class="small text-muted mb-0">3</p>
              </div>
            </div>
          </div>
        </div>

        <div class="card mb-4">
          <div class="card-body">
            <p>Type your note, and hit enter to add it</p>

            <div class="d-flex justify-content-between">
              <div class="d-flex flex-row align-items-center">
                <img
                  src="https://mdbootstrap.com/img/Photos/Avatars/img%20(32).jpg"
                  alt="avatar"
                  width="25"
                  height="25"
                />
                <p class="small mb-0 ms-2">Johny</p>
              </div>
              <div class="d-flex flex-row align-items-center">
                <p class="small text-muted mb-0">Upvote?</p>
                <i
                  class="far fa-thumbs-up mx-2 fa-xs text-black"
                  style="margin-top: -0.16rem;"
                ></i>
                <p class="small text-muted mb-0">4</p>
              </div>
            </div>
          </div>
        </div>

        <div class="card mb-4">
          <div class="card-body">
            <p>Type your note, and hit enter to add it</p>

            <div class="d-flex justify-content-between">
              <div class="d-flex flex-row align-items-center">
                <img
                  src="https://mdbootstrap.com/img/Photos/Avatars/img%20(31).jpg"
                  alt="avatar"
                  width="25"
                  height="25"
                />
                <p class="small mb-0 ms-2">Mary Kate</p>
              </div>
              <div class="d-flex flex-row align-items-center text-primary">
                <p class="small mb-0">Upvoted</p>
                <i class="fas fa-thumbs-up mx-2 fa-xs" style="margin-top: -0.16rem;"></i>
                <p class="small mb-0">2</p>
              </div>
            </div>
          </div>
        </div>

        <div class="card">
          <div class="card-body">
            <p>Type your note, and hit enter to add it</p>

            <div class="d-flex justify-content-between">
              <div class="d-flex flex-row align-items-center">
                <img
                  src="https://mdbootstrap.com/img/Photos/Avatars/img%20(32).jpg"
                  alt="avatar"
                  width="25"
                  height="25"
                />
                <p class="small mb-0 ms-2">Johny</p>
              </div>
              <div class="d-flex flex-row align-items-center">
                <p class="small text-muted mb-0">Upvote?</p>
                <i
                  class="far fa-thumbs-up ms-2 fa-xs text-black"
                  style="margin-top: -0.16rem;"
                ></i>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```

#### Much more examples and a detailed description can be found at [📄 Comments documentation page](https://mdbootstrap.com/docs/standard/extended/comments/)
