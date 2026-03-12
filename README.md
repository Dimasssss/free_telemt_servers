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

# Server Metrics 2026-03-12 14:15:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 24106.7 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127550
telemt_connections_bad_total 1372
telemt_handshake_timeouts_total 4467
telemt_upstream_connect_attempt_total 5915
telemt_upstream_connect_success_total 5891
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 254
telemt_me_reconnect_attempts_total 4682
telemt_me_reconnect_success_total 4651
telemt_me_reader_eof_total 4885
telemt_me_idle_close_by_peer_total 4884
telemt_me_route_drop_no_conn_total 35845
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111745
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 529
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4692
telemt_me_writer_restored_same_endpoint_total 4635
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 111711
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 1875166248 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 42223183688 (39.32 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23999.4 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52224
telemt_connections_bad_total 441
telemt_handshake_timeouts_total 360
telemt_upstream_connect_attempt_total 7079
telemt_upstream_connect_success_total 6912
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 7079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 21526
telemt_me_reconnect_success_total 5693
telemt_me_reader_eof_total 6302
telemt_me_idle_close_by_peer_total 6302
telemt_me_route_drop_no_conn_total 23474
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49826
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6223
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5678
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 49820
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 582216796 (555.25 MB)
telemt_user_octets_to_client{user="hello"} 14150500544 (13.18 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23963.1 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72018
telemt_connections_bad_total 1383
telemt_handshake_timeouts_total 870
telemt_upstream_connect_attempt_total 6443
telemt_upstream_connect_success_total 6443
telemt_upstream_connect_attempts_per_request{bucket="1"} 6443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 5230
telemt_me_reconnect_success_total 5190
telemt_me_reader_eof_total 5490
telemt_me_idle_close_by_peer_total 5490
telemt_me_route_drop_no_conn_total 25084
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66657
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5226
telemt_me_writer_restored_same_endpoint_total 5170
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 66637
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1869059540 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 37532274700 (34.95 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23938.7 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91389
telemt_connections_bad_total 1513
telemt_handshake_timeouts_total 683
telemt_upstream_connect_attempt_total 6331
telemt_upstream_connect_success_total 6170
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 6331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 18040
telemt_me_reconnect_success_total 4932
telemt_me_reader_eof_total 5473
telemt_me_idle_close_by_peer_total 5473
telemt_me_route_drop_no_conn_total 34105
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83879
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 260
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5398
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 4924
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 83762
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 1381676316 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 35387024024 (32.96 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 23908.2 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53619
telemt_connections_bad_total 4527
telemt_handshake_timeouts_total 701
telemt_upstream_connect_attempt_total 19693
telemt_upstream_connect_success_total 19394
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 19693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 31455
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4548
telemt_me_idle_close_by_peer_total 4548
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12195
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32630
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 442
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4573
telemt_me_refill_failed_total 869
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 889
telemt_user_connections_total{user="hello"} 47105
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 389693157 (371.64 MB)
telemt_user_octets_to_client{user="hello"} 11857508345 (11.04 GB)
telemt_user_msgs_from_client{user="hello"} 206222
telemt_user_msgs_to_client{user="hello"} 602753
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 23895.5 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144314
telemt_connections_bad_total 776
telemt_handshake_timeouts_total 1100
telemt_upstream_connect_attempt_total 4936
telemt_upstream_connect_success_total 4912
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 4936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 3717
telemt_me_reconnect_success_total 3687
telemt_me_reader_eof_total 3884
telemt_me_idle_close_by_peer_total 3884
telemt_me_route_drop_no_conn_total 56945
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137931
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 229
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3731
telemt_me_writer_restored_same_endpoint_total 3680
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 137898
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 2838015956 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 57558292780 (53.61 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 68
```