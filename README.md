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

# Server Metrics 2026-03-12 13:19:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20738.3 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109822
telemt_connections_bad_total 546
telemt_handshake_timeouts_total 3754
telemt_upstream_connect_attempt_total 5039
telemt_upstream_connect_success_total 5015
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 3973
telemt_me_reconnect_success_total 3947
telemt_me_reader_eof_total 4127
telemt_me_idle_close_by_peer_total 4126
telemt_me_route_drop_no_conn_total 31133
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97846
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 462
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3977
telemt_me_writer_restored_same_endpoint_total 3931
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 97811
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 1383457504 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 37398219468 (34.83 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 20632.1 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44599
telemt_connections_bad_total 336
telemt_handshake_timeouts_total 340
telemt_upstream_connect_attempt_total 6149
telemt_upstream_connect_success_total 5996
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 6149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 20784
telemt_me_reconnect_success_total 4957
telemt_me_reader_eof_total 5513
telemt_me_idle_close_by_peer_total 5513
telemt_me_route_drop_no_conn_total 19162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42522
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 5477
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 4942
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 42521
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 506818560 (483.34 MB)
telemt_user_octets_to_client{user="hello"} 11863471236 (11.05 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 20596.0 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60248
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 637
telemt_upstream_connect_attempt_total 5644
telemt_upstream_connect_success_total 5644
telemt_upstream_connect_attempts_per_request{bucket="1"} 5644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 4609
telemt_me_reconnect_success_total 4577
telemt_me_reader_eof_total 4817
telemt_me_idle_close_by_peer_total 4817
telemt_me_route_drop_no_conn_total 20988
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56730
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4605
telemt_me_writer_restored_same_endpoint_total 4557
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 56712
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 1780156508 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 34021535360 (31.69 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 20571.3 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77113
telemt_connections_bad_total 1095
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 5651
telemt_upstream_connect_success_total 5507
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 5651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 199
telemt_me_reconnect_attempts_total 12180
telemt_me_reconnect_success_total 4450
telemt_me_reader_eof_total 4820
telemt_me_idle_close_by_peer_total 4820
telemt_me_route_drop_no_conn_total 26053
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70800
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 210
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4744
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 4442
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 70800
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 1197347832 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 32720807316 (30.47 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20540.8 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44545
telemt_connections_bad_total 3881
telemt_handshake_timeouts_total 656
telemt_upstream_connect_attempt_total 12484
telemt_upstream_connect_success_total 12245
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 12484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 25900
telemt_me_reconnect_success_total 3635
telemt_me_reader_eof_total 4327
telemt_me_idle_close_by_peer_total 4327
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 11770
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31362
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 404
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4352
telemt_me_refill_failed_total 697
telemt_me_writer_restored_same_endpoint_total 3618
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 38914
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 303633195 (289.57 MB)
telemt_user_octets_to_client{user="hello"} 10255430428 (9.55 GB)
telemt_user_msgs_from_client{user="hello"} 102522
telemt_user_msgs_to_client{user="hello"} 325145
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 20527.9 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118917
telemt_connections_bad_total 768
telemt_handshake_timeouts_total 959
telemt_upstream_connect_attempt_total 4224
telemt_upstream_connect_success_total 4202
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 3184
telemt_me_reconnect_success_total 3156
telemt_me_reader_eof_total 3315
telemt_me_idle_close_by_peer_total 3315
telemt_me_route_drop_no_conn_total 48343
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113285
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 216
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3195
telemt_me_writer_restored_same_endpoint_total 3149
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 113253
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 2626345176 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 50426240924 (46.96 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 52
```