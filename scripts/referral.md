# Referrals

## Hypothesis

People who commit to an event will be enthusiastic about the service, and will tell others about it, producing a word-of-mouth effect.

## Metric

Number of signups with a referral code should increase.

## Script

### At beginning

- Let's make everyday activism go viral, so everyone can get involved in building their community. Send this message as a WhatsApp broadcast to your friends and neighbours by clicking `FORM_URL`?code=`CODE_HERE` and then choosing your contacts.

### After committing
- Before you go, let's make everyday activism go viral, so everyone can get involved. Send an invite to three friends by clicking the link below and then choosing your contacts: [link]
> ^ generate that link from this code in the browser console
> console.log("https://api.whatsapp.com/send?text="+encodeURIComponent("I just tried Movement, a service which gets you involved as fast as possible with grassroots activism, so you can put your principles into practice. Recommend you check it out: https://commonknowledge.coop/movement?code=Welcome🙌A61"))
> Pipe it through https://bitly.com/ to shorten the URL