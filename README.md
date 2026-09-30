# tela-load
import { StyleSheet, Text, View, Image } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>

      <View style={styles.body}>

        <Image
          style={styles.logo}
          source={{
            uri: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ7C0NlbHXsMpd67_3fP8sauaf7Xy2cDkCNMVcN6imz158sgpE0eFyx_5xK&s=10'
          }}
        />

        <Text style={styles.title}>
          COLÔNIA MARTE
        </Text>

        <Text style={styles.subtitle}>
          BASE HUMANA • SETOR A-01
        </Text>

        <Text style={styles.paragraph1}>
          Onde novos mundos começam...
        </Text>

        <View style={styles.statusBox}>
          <Text style={styles.status}>
            ● SISTEMA DA COLÔNIA ONLINE
          </Text>
        </View>

      </View>

      <View style={styles.footer}>
        <Text style={styles.paragraph2}>
          v1.0 - Rafael Batista
        </Text>

        <Text style={styles.mars}>
          MARTE • 01
        </Text>
      </View>

    </View>
  );
}

const styles = StyleSheet.create({

  container: {
    flex: 1,
    backgroundColor: '#160b08',
  },

  body: {
    flex: 6,
    justifyContent: 'center',
    alignItems: 'center',

    backgroundColor: '#1e0e0a',

    margin: 20,
    marginBottom: 0,

    borderWidth: 1,
    borderColor: '#5c2b1c',

    borderRadius: 12,

    borderLeftWidth: 4,
    borderLeftColor: '#e85d04',
  },

  logo: {
    width: 100,
    height: 100,

    borderRadius: 50,

    marginBottom: 15,

    borderWidth: 3,
    borderColor: '#e85d04',
  },

  title: {
    color: '#ff6b35',

    fontSize: 36,

    fontWeight: 'bold',

    letterSpacing: 2,

    marginBottom: 5,
  },

  subtitle: {
    color: '#b88972',

    fontSize: 11,

    letterSpacing: 1,

    marginBottom: 20,
  },

  paragraph1: {
    color: '#f4d6bd',

    fontSize: 14,

    fontStyle: 'italic',
  },

  statusBox: {
    marginTop: 25,

    paddingVertical: 8,
    paddingHorizontal: 15,

    borderRadius: 6,

    backgroundColor: '#28130e',

    borderWidth: 1,
    borderColor: '#542719',
  },

  status: {
    color: '#52b788',

    fontSize: 10,

    fontWeight: 'bold',

    letterSpacing: 1,
  },

  footer: {
    flex: 1,

    justifyContent: 'center',
    alignItems: 'center',

    borderTopWidth: 2,
    borderColor: '#5c2b1c',

    backgroundColor: '#1e0e0a',
  },

  paragraph2: {
    color: '#987c70',

    fontSize: 12,

    marginBottom: 5,
  },

  mars: {
    color: '#e85d04',

    fontSize: 9,

    fontWeight: 'bold',

    letterSpacing: 2,
  },

});
