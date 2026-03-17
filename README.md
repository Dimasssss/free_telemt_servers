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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 07:05:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 44394.9 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279035
telemt_connections_bad_total 3388
telemt_handshake_timeouts_total 8712
telemt_upstream_connect_attempt_total 9218
telemt_upstream_connect_success_total 9168
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6975
telemt_me_reconnect_success_total 6948
telemt_me_reader_eof_total 7399
telemt_me_idle_close_by_peer_total 7399
telemt_me_route_drop_no_conn_total 85052
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250400
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1830
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1272
telemt_desync_frames_bucket_total{bucket="1_2"} 412
telemt_desync_frames_bucket_total{bucket="3_10"} 921
telemt_desync_frames_bucket_total{bucket="gt_10"} 497
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7019
telemt_me_writer_restored_same_endpoint_total 6927
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 250182
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 3277756772 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 108273534852 (100.84 GB)
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 44646.4 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156966
telemt_connections_bad_total 2211
telemt_handshake_timeouts_total 11675
telemt_upstream_connect_attempt_total 12260
telemt_upstream_connect_success_total 12105
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 12260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 11075
telemt_me_reconnect_success_total 9893
telemt_me_reader_eof_total 10461
telemt_me_idle_close_by_peer_total 10461
telemt_me_route_drop_no_conn_total 57169
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135717
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 374
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10021
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9877
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 135754
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 1664915004 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 58064653292 (54.08 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 44422.5 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93053
telemt_connections_bad_total 1132
telemt_handshake_timeouts_total 3433
telemt_upstream_connect_attempt_total 11781
telemt_upstream_connect_success_total 11719
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9532
telemt_me_reconnect_success_total 9478
telemt_me_reader_eof_total 10147
telemt_me_idle_close_by_peer_total 10147
telemt_me_route_drop_no_conn_total 31271
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80082
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 81
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9593
telemt_me_writer_restored_same_endpoint_total 9467
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 80040
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 6247047400 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 25448142816 (23.70 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 44481.7 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175075
telemt_connections_bad_total 5823
telemt_handshake_timeouts_total 9652
telemt_upstream_connect_attempt_total 10179
telemt_upstream_connect_success_total 10095
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 10179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 7876
telemt_me_reconnect_success_total 7814
telemt_me_reader_eof_total 8305
telemt_me_idle_close_by_peer_total 8305
telemt_me_route_drop_no_conn_total 55202
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151434
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 280
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7925
telemt_me_writer_restored_same_endpoint_total 7806
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 151445
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 1624613118 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 71151473925 (66.26 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 44453.7 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125259
telemt_connections_bad_total 37705
telemt_handshake_timeouts_total 2385
telemt_upstream_connect_attempt_total 13530
telemt_upstream_connect_success_total 13354
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 13530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_reconnect_attempts_total 14273
telemt_me_reconnect_success_total 11011
telemt_me_reader_eof_total 11631
telemt_me_idle_close_by_peer_total 11631
telemt_me_route_drop_no_conn_total 32534
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81808
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 68
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 11253
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11003
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 81854
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 829099491 (790.69 MB)
telemt_user_octets_to_client{user="hello"} 37915133750 (35.31 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 44615.9 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296404
telemt_connections_bad_total 42156
telemt_handshake_timeouts_total 2409
telemt_upstream_connect_attempt_total 9112
telemt_upstream_connect_success_total 9064
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 6876
telemt_me_reconnect_success_total 6844
telemt_me_reader_eof_total 7326
telemt_me_idle_close_by_peer_total 7326
telemt_me_route_drop_no_conn_total 229778
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318423
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 330
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 179
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 6946
telemt_me_writer_restored_same_endpoint_total 6830
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 240363
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 3468370372 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 158604658372 (147.71 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 32621.2 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1416
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 16405
telemt_upstream_connect_success_total 16404
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14775
telemt_me_reconnect_success_total 14691
telemt_me_reader_eof_total 16082
telemt_me_idle_close_by_peer_total 16082
telemt_me_route_drop_no_conn_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1207
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 14822
telemt_me_writer_restored_same_endpoint_total 14691
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 1207
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 205918680 (196.38 MB)
telemt_user_octets_to_client{user="hello"} 13285465116 (12.37 GB)
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```