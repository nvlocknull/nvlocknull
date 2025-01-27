```node
class Nvlock {
    constructor() {
        this.alias  = [ 'nvlock', 'xseven' ]
    }

    contact() {
        const discord  = 'nvlock'
        const telegram = 't.me/nvlock'
        const email    = 'nvlock@stormmedia.gg'
        
        return discord, telegram, email
    }

    life() {
        const age        = 18
        const occupation = 'Student'
        const hobbies    = [ 'Programming', 'Cracking' ]
        
        return age, occupation, hobbies
    }

    programming() {
        const languages         = [ 'JavaScript, TypeScript (Node.js Framework)', 'Python', 'Lua', 'C#' ];
        const learning          = [ 'C++' ];
        const ide               = 'Visual Studio Code';

        const preferredLanguage = languages[0];

        return languages, learning, ide, preferredLanguage
    }
}

module.exports = Nvlock
