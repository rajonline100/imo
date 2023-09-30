# imo
554385
<manifest ... >
    <application ... >
        <activity android:name="com.example.myapp.MainActivity" ... >
        </activity>
    </application>
</manifest>Auth.auth().addStateDidChangeListener { (auth, user) in
  if let user = user {
    let email = user.email
    // ...
  }
}
Auth.auth().signIn(withEmail: userEmail, password: password) { (user, error) in
  if let user = user {
    // ...
  }
}
