# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-14 22:25:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 674.4 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1761
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 179
telemt_upstream_connect_success_total 177
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 65
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 114
telemt_me_reconnect_success_total 112
telemt_me_reader_eof_total 74
telemt_me_idle_close_by_peer_total 74
telemt_me_route_drop_no_conn_total 279
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1616
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 96
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 1616
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 19866316 (18.95 MB)
telemt_user_octets_to_client{user="hello"} 341776088 (325.94 MB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 680.8 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 240
telemt_upstream_connect_success_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 147
telemt_me_reconnect_attempts_total 172
telemt_me_reconnect_success_total 172
telemt_me_reader_eof_total 145
telemt_me_idle_close_by_peer_total 145
telemt_me_route_drop_no_conn_total 205
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 162
telemt_me_writer_restored_same_endpoint_total 156
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 509
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 2129160 (2.03 MB)
telemt_user_octets_to_client{user="hello"} 29587140 (28.22 MB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 673.4 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 173
telemt_upstream_connect_success_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_me_reconnect_attempts_total 106
telemt_me_reconnect_success_total 104
telemt_me_reader_eof_total 81
telemt_me_idle_close_by_peer_total 81
telemt_me_route_drop_no_conn_total 138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 835
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 93
telemt_me_writer_restored_same_endpoint_total 100
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 835
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 66206064 (63.14 MB)
telemt_user_octets_to_client{user="hello"} 551555300 (526.00 MB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 673.0 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697
telemt_upstream_connect_attempt_total 158
telemt_upstream_connect_success_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 95
telemt_me_reconnect_success_total 93
telemt_me_reader_eof_total 65
telemt_me_idle_close_by_peer_total 65
telemt_me_route_drop_no_conn_total 178
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 679
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 679
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 6856304 (6.54 MB)
telemt_user_octets_to_client{user="hello"} 1758396852 (1.64 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 673.2 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1032
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 173
telemt_upstream_connect_success_total 171
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 110
telemt_me_reconnect_success_total 110
telemt_me_reader_eof_total 74
telemt_me_idle_close_by_peer_total 74
telemt_me_route_drop_no_conn_total 163
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 886
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 90
telemt_me_writer_restored_same_endpoint_total 98
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 886
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 4837048 (4.61 MB)
telemt_user_octets_to_client{user="hello"} 312059036 (297.60 MB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 672.2 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2271
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 189
telemt_upstream_connect_success_total 188
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 123
telemt_me_reconnect_success_total 123
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2209
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 11
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_restored_same_endpoint_total 96
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 2209
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 26722456 (25.48 MB)
telemt_user_octets_to_client{user="hello"} 2746667400 (2.56 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 30
```