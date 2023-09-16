#### Support Email Response
class TestMailer < ActionMailer::Base
  default from: '@example.com'
  def simple_message(recipient)
    mail(
      to: recipient,
      subject: 'Support Email response ',
      body: 'We are looking into the matter and will inform soon on the updates'
    )
  end
end
[your response goes here]

---

#### Support Email Troubleshooting steps

[your response here]

---

#### Community Forum Response

[your response here]

---

#### Rails App URL

Once you've deployed your Rails app, put the link here: `<app>.fly.dev`
