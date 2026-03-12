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

# Server Metrics 2026-03-12 23:06:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 56008.1 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248368
telemt_connections_bad_total 2720
telemt_handshake_timeouts_total 5252
telemt_upstream_connect_attempt_total 14083
telemt_upstream_connect_success_total 14021
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 14083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1479
telemt_me_reconnect_attempts_total 14637
telemt_me_reconnect_success_total 11167
telemt_me_reader_eof_total 11902
telemt_me_idle_close_by_peer_total 11901
telemt_me_route_drop_no_conn_total 76853
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204751
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 433
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11401
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11151
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 204517
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 3813623020 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 104116020784 (96.97 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 55901.7 (15h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112577
telemt_connections_bad_total 569
telemt_handshake_timeouts_total 831
telemt_upstream_connect_attempt_total 32713
telemt_upstream_connect_success_total 32346
telemt_upstream_connect_fail_total 367
telemt_upstream_connect_attempts_per_request{bucket="1"} 32713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 367
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 54884
telemt_me_reconnect_success_total 13015
telemt_me_reader_eof_total 14631
telemt_me_idle_close_by_peer_total 14631
telemt_me_route_drop_no_conn_total 41049
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90501
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 14416
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 13000
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1401
telemt_user_connections_total{user="hello"} 107003
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1198695020 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 33838251255 (31.51 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 55865.3 (15h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138327
telemt_connections_bad_total 1607
telemt_handshake_timeouts_total 2223
telemt_upstream_connect_attempt_total 15354
telemt_upstream_connect_success_total 15353
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 13636
telemt_me_reconnect_success_total 12489
telemt_me_reader_eof_total 13321
telemt_me_idle_close_by_peer_total 13321
telemt_me_route_drop_no_conn_total 51948
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129287
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12646
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 12469
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 129253
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 2581829252 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 60503842260 (56.35 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 55840.9 (15h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201886
telemt_connections_bad_total 13259
telemt_handshake_timeouts_total 1372
telemt_upstream_connect_attempt_total 26802
telemt_upstream_connect_success_total 17106
telemt_upstream_connect_fail_total 9696
telemt_upstream_connect_attempts_per_request{bucket="1"} 26802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9696
telemt_me_keepalive_timeout_total 2490
telemt_me_reconnect_attempts_total 43682
telemt_me_reconnect_success_total 11435
telemt_me_reader_eof_total 12843
telemt_me_idle_close_by_peer_total 12836
telemt_me_route_drop_no_conn_total 71026
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165953
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 12616
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 11425
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1181
telemt_user_connections_total{user="hello"} 168707
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 2978842314 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 68358527849 (63.66 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6012.5 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5770
telemt_connections_bad_total 1079
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1760
telemt_upstream_connect_success_total 1741
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1415
telemt_me_reconnect_success_total 1414
telemt_me_reader_eof_total 1495
telemt_me_idle_close_by_peer_total 1495
telemt_me_route_drop_no_conn_total 1575
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4494
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1419
telemt_me_writer_restored_same_endpoint_total 1398
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 4494
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 12205524 (11.64 MB)
telemt_user_octets_to_client{user="hello"} 1298491324 (1.21 GB)
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 55797.4 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329321
telemt_connections_bad_total 5143
telemt_handshake_timeouts_total 2511
telemt_upstream_connect_attempt_total 11683
telemt_upstream_connect_success_total 11620
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 11683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 12453
telemt_me_reconnect_success_total 8840
telemt_me_reader_eof_total 9448
telemt_me_idle_close_by_peer_total 9447
telemt_me_route_drop_no_conn_total 148531
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323720
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9060
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8833
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 312022
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 5468268092 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 166921424348 (155.46 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 22
```