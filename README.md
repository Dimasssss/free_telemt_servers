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

# Server Metrics 2026-03-13 03:32:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 71969.3 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279601
telemt_connections_bad_total 2923
telemt_handshake_timeouts_total 5742
telemt_upstream_connect_attempt_total 18182
telemt_upstream_connect_success_total 18101
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 18182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1529
telemt_me_reconnect_attempts_total 17982
telemt_me_reconnect_success_total 14495
telemt_me_reader_eof_total 15490
telemt_me_idle_close_by_peer_total 15489
telemt_me_route_drop_no_conn_total 87060
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233367
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 776
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 14762
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14479
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 233307
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 4107506268 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 114808750704 (106.92 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 71862.0 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128937
telemt_connections_bad_total 745
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 39426
telemt_upstream_connect_success_total 38950
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 39426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_keepalive_timeout_total 524
telemt_me_reconnect_attempts_total 65418
telemt_me_reconnect_success_total 18860
telemt_me_reader_eof_total 20850
telemt_me_idle_close_by_peer_total 20850
telemt_me_route_drop_no_conn_total 46341
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105978
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 20457
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 18845
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1597
telemt_user_connections_total{user="hello"} 122478
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 1279921976 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 36209253575 (33.72 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 71825.5 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155014
telemt_connections_bad_total 1826
telemt_handshake_timeouts_total 2437
telemt_upstream_connect_attempt_total 19923
telemt_upstream_connect_success_total 19921
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 19923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 395
telemt_me_reconnect_attempts_total 17451
telemt_me_reconnect_success_total 16289
telemt_me_reader_eof_total 17423
telemt_me_idle_close_by_peer_total 17423
telemt_me_route_drop_no_conn_total 59587
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145021
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
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 16466
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 16269
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 144946
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 2748613780 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 68788592492 (64.06 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 71801.2 (19h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222435
telemt_connections_bad_total 13467
telemt_handshake_timeouts_total 1439
telemt_upstream_connect_attempt_total 32156
telemt_upstream_connect_success_total 22322
telemt_upstream_connect_fail_total 9834
telemt_upstream_connect_attempts_per_request{bucket="1"} 32156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9834
telemt_me_keepalive_timeout_total 3300
telemt_me_reconnect_attempts_total 59398
telemt_me_reconnect_success_total 15871
telemt_me_reader_eof_total 17747
telemt_me_idle_close_by_peer_total 17740
telemt_me_route_drop_no_conn_total 81013
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185497
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 502
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 17448
telemt_me_refill_failed_total 1356
telemt_me_writer_restored_same_endpoint_total 15861
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1577
telemt_user_connections_total{user="hello"} 188247
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 3145517798 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 76915817681 (71.63 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21973.0 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21184
telemt_connections_bad_total 4125
telemt_handshake_timeouts_total 47
telemt_upstream_connect_attempt_total 6929
telemt_upstream_connect_success_total 6865
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 6929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 5766
telemt_me_reconnect_success_total 5748
telemt_me_reader_eof_total 6158
telemt_me_idle_close_by_peer_total 6158
telemt_me_route_drop_no_conn_total 6178
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16410
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5793
telemt_me_writer_restored_same_endpoint_total 5730
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 16410
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 120778964 (115.18 MB)
telemt_user_octets_to_client{user="hello"} 7023641664 (6.54 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 71757.6 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375074
telemt_connections_bad_total 6674
telemt_handshake_timeouts_total 2864
telemt_upstream_connect_attempt_total 15297
telemt_upstream_connect_success_total 15211
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 15297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1413
telemt_me_reconnect_attempts_total 15268
telemt_me_reconnect_success_total 11643
telemt_me_reader_eof_total 12504
telemt_me_idle_close_by_peer_total 12501
telemt_me_route_drop_no_conn_total 168353
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366687
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
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 11904
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11636
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 354933
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 5970225076 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 213788811560 (199.11 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 34
```