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

# Server Metrics 2026-03-14 21:09:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 28367.6 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140406
telemt_connections_bad_total 16262
telemt_handshake_timeouts_total 1502
telemt_upstream_connect_attempt_total 6380
telemt_upstream_connect_success_total 6378
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 221
telemt_me_reconnect_attempts_total 4959
telemt_me_reconnect_success_total 4921
telemt_me_reader_eof_total 5223
telemt_me_idle_close_by_peer_total 5223
telemt_me_route_drop_no_conn_total 51005
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116340
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 555
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 361
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 201
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5003
telemt_me_writer_restored_same_endpoint_total 4903
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 116260
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 2477017184 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 69705322392 (64.92 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 28365.9 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58073
telemt_connections_bad_total 731
telemt_handshake_timeouts_total 991
telemt_upstream_connect_attempt_total 7387
telemt_upstream_connect_success_total 7340
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 7387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 8462
telemt_me_reconnect_success_total 5882
telemt_me_reader_eof_total 6256
telemt_me_idle_close_by_peer_total 6256
telemt_me_route_drop_no_conn_total 31247
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54158
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 6040
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5877
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 54080
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1369400476 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 24384393372 (22.71 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 28370.3 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65029
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 1893
telemt_upstream_connect_attempt_total 9248
telemt_upstream_connect_success_total 9152
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 9248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 255
telemt_me_reconnect_attempts_total 105242
telemt_me_reconnect_success_total 7377
telemt_me_reader_eof_total 7890
telemt_me_idle_close_by_peer_total 7890
telemt_me_route_drop_no_conn_total 24480
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59414
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7659
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7331
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 59477
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 3882726377 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 42676377098 (39.75 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 28375.2 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83011
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 609
telemt_upstream_connect_attempt_total 6967
telemt_upstream_connect_success_total 6924
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 6967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 194
telemt_me_reconnect_attempts_total 5331
telemt_me_reconnect_success_total 5303
telemt_me_reader_eof_total 5588
telemt_me_idle_close_by_peer_total 5588
telemt_me_route_drop_no_conn_total 35739
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78669
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 636
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5362
telemt_me_writer_restored_same_endpoint_total 5301
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 78715
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1299371320 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 27501628426 (25.61 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 28368.4 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61167
telemt_connections_bad_total 5496
telemt_handshake_timeouts_total 3340
telemt_upstream_connect_attempt_total 6897
telemt_upstream_connect_success_total 6818
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 6897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 11894
telemt_me_reconnect_success_total 5357
telemt_me_reader_eof_total 5805
telemt_me_idle_close_by_peer_total 5805
telemt_me_route_drop_no_conn_total 19970
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49430
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5611
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5353
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 49417
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 1388292728 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 30489588872 (28.40 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 28368.1 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208903
telemt_connections_bad_total 7317
telemt_handshake_timeouts_total 2671
telemt_upstream_connect_attempt_total 5616
telemt_upstream_connect_success_total 5511
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 5616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 256
telemt_me_reconnect_attempts_total 9062
telemt_me_reconnect_success_total 4053
telemt_me_reader_eof_total 4384
telemt_me_idle_close_by_peer_total 4384
telemt_me_route_drop_no_conn_total 116819
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192832
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 106
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4258
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4049
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 189318
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 4187876172 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 102911714080 (95.84 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 35
```