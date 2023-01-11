<template>
    <div class="contact">
        <form action="https://formspree.io/f/mvoyrloq" method="post">
            <div>
                <div>
                    <div>
                        <div>
                            <p> contact via email <br>Or<br>tel:064 5997 0651 </p>
                        </div>
                        <div>
                            <label for="#firstname">Name</label>
                            <label for="#surname">Surname</label>
                            <label for="#message">Message</label>
                        </div>
                        <div>
                            <input name="firstName" type="text" placeholder="Enter your name" required>
                            <input name="surname" type="text" placeholder="Enter your surname" required>
                            <textarea name="message" type="text" placeholder="Enter your message"></textarea>
                            <button type="submit">Submit</button>
                        </div>
                    </div>
                </div>
            </div>
        </form>
    </div>
</template>