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

# Server Metrics 2026-03-13 03:12:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 70741.2 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277004
telemt_connections_bad_total 2917
telemt_handshake_timeouts_total 5705
telemt_upstream_connect_attempt_total 17917
telemt_upstream_connect_success_total 17838
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 17917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1526
telemt_me_reconnect_attempts_total 17762
telemt_me_reconnect_success_total 14277
telemt_me_reader_eof_total 15258
telemt_me_idle_close_by_peer_total 15257
telemt_me_route_drop_no_conn_total 86270
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230996
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 14541
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14261
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 230856
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 4071388436 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 113385405288 (105.60 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 70634.4 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127708
telemt_connections_bad_total 744
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 38964
telemt_upstream_connect_success_total 38489
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 38963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_keepalive_timeout_total 520
telemt_me_reconnect_attempts_total 65002
telemt_me_reconnect_success_total 18445
telemt_me_reader_eof_total 20395
telemt_me_idle_close_by_peer_total 20395
telemt_me_route_drop_no_conn_total 45892
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104782
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 20040
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 18430
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1595
telemt_user_connections_total{user="hello"} 121282
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 1271119500 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 35819093103 (33.36 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 70598.1 (19h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153780
telemt_connections_bad_total 1825
telemt_handshake_timeouts_total 2434
telemt_upstream_connect_attempt_total 19600
telemt_upstream_connect_success_total 19598
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 19600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 391
telemt_me_reconnect_attempts_total 17171
telemt_me_reconnect_success_total 16009
telemt_me_reader_eof_total 17124
telemt_me_idle_close_by_peer_total 17124
telemt_me_route_drop_no_conn_total 59013
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143845
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 16185
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 15989
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 143770
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 2741766952 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 68687139588 (63.97 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 70573.8 (19h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220433
telemt_connections_bad_total 13466
telemt_handshake_timeouts_total 1439
telemt_upstream_connect_attempt_total 31882
telemt_upstream_connect_success_total 22052
telemt_upstream_connect_fail_total 9830
telemt_upstream_connect_attempts_per_request{bucket="1"} 31882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9830
telemt_me_keepalive_timeout_total 3296
telemt_me_reconnect_attempts_total 59171
telemt_me_reconnect_success_total 15645
telemt_me_reader_eof_total 17508
telemt_me_idle_close_by_peer_total 17501
telemt_me_route_drop_no_conn_total 80213
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183545
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 15
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 17220
telemt_me_refill_failed_total 1356
telemt_me_writer_restored_same_endpoint_total 15635
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1575
telemt_user_connections_total{user="hello"} 186296
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 3131499442 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 76098929217 (70.87 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20745.2 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19691
telemt_connections_bad_total 3890
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6331
telemt_upstream_connect_success_total 6274
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 6331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 5250
telemt_me_reconnect_success_total 5233
telemt_me_reader_eof_total 5610
telemt_me_idle_close_by_peer_total 5610
telemt_me_route_drop_no_conn_total 5653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15229
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5275
telemt_me_writer_restored_same_endpoint_total 5217
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 15229
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 116003580 (110.63 MB)
telemt_user_octets_to_client{user="hello"} 6920216372 (6.44 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 70530.1 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371853
telemt_connections_bad_total 6633
telemt_handshake_timeouts_total 2858
telemt_upstream_connect_attempt_total 15049
telemt_upstream_connect_success_total 14965
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 15049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1397
telemt_me_reconnect_attempts_total 15064
telemt_me_reconnect_success_total 11442
telemt_me_reader_eof_total 12286
telemt_me_idle_close_by_peer_total 12283
telemt_me_route_drop_no_conn_total 166634
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363575
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 11696
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11435
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 351821
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 5934474696 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 212926805116 (198.30 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 23
```