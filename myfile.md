function shout(string){
return string.toUpperCase();
}

function whisper(string){
    return string.toLowerCase();
}

function logShout(string){
    console.log('hello'.toUpperCase());
}


function logWhisper(string){
    console.log('HELLO'.toLowerCase());
}

function sayHiToHeadphonedRoommate(string){
    if (string===string.toLowerCase()){
        return 'I can\'t hear you!'
    }