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

# Server Metrics 2026-03-13 02:26:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 67978.5 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270632
telemt_connections_bad_total 2811
telemt_handshake_timeouts_total 5644
telemt_upstream_connect_attempt_total 17242
telemt_upstream_connect_success_total 17167
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 17242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1520
telemt_me_reconnect_attempts_total 17220
telemt_me_reconnect_success_total 13739
telemt_me_reader_eof_total 14674
telemt_me_idle_close_by_peer_total 14673
telemt_me_route_drop_no_conn_total 84084
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225169
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 738
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 273
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13995
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13723
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 224935
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 3998710400 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 110882600996 (103.27 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 67871.5 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125483
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 37381
telemt_upstream_connect_success_total 36923
telemt_upstream_connect_fail_total 458
telemt_upstream_connect_attempts_per_request{bucket="1"} 37381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 502
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 458
telemt_me_keepalive_timeout_total 480
telemt_me_reconnect_attempts_total 61228
telemt_me_reconnect_success_total 17011
telemt_me_reader_eof_total 18875
telemt_me_idle_close_by_peer_total 18875
telemt_me_route_drop_no_conn_total 45164
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102641
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
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
telemt_me_writer_removed_unexpected_total 18520
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 16996
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1509
telemt_user_connections_total{user="hello"} 119142
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 1260142248 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 35553357403 (33.11 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 67835.0 (18h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151349
telemt_connections_bad_total 1822
telemt_handshake_timeouts_total 2419
telemt_upstream_connect_attempt_total 18888
telemt_upstream_connect_success_total 18886
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 377
telemt_me_reconnect_attempts_total 16592
telemt_me_reconnect_success_total 15432
telemt_me_reader_eof_total 16499
telemt_me_idle_close_by_peer_total 16499
telemt_me_route_drop_no_conn_total 57727
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141489
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
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 15600
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 15412
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 141427
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 2715551108 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 67081869408 (62.47 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 67810.8 (18h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216319
telemt_connections_bad_total 13408
telemt_handshake_timeouts_total 1429
telemt_upstream_connect_attempt_total 31165
telemt_upstream_connect_success_total 21365
telemt_upstream_connect_fail_total 9800
telemt_upstream_connect_attempts_per_request{bucket="1"} 31165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9800
telemt_me_keepalive_timeout_total 3270
telemt_me_reconnect_attempts_total 54582
telemt_me_reconnect_success_total 15090
telemt_me_reader_eof_total 16824
telemt_me_idle_close_by_peer_total 16817
telemt_me_route_drop_no_conn_total 78368
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179627
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_me_writer_removed_unexpected_total 16536
telemt_me_refill_failed_total 1230
telemt_me_writer_restored_same_endpoint_total 15080
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1446
telemt_user_connections_total{user="hello"} 182378
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 3057416702 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 75246306801 (70.08 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17982.4 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16480
telemt_connections_bad_total 3371
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 5502
telemt_upstream_connect_success_total 5451
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 5502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 4567
telemt_me_reconnect_success_total 4550
telemt_me_reader_eof_total 4874
telemt_me_idle_close_by_peer_total 4874
telemt_me_route_drop_no_conn_total 4907
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4589
telemt_me_writer_restored_same_endpoint_total 4534
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 12594
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 82472808 (78.65 MB)
telemt_user_octets_to_client{user="hello"} 6221248324 (5.79 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 67767.3 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363786
telemt_connections_bad_total 6622
telemt_handshake_timeouts_total 2844
telemt_upstream_connect_attempt_total 14475
telemt_upstream_connect_success_total 14393
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1349
telemt_me_reconnect_attempts_total 14623
telemt_me_reconnect_success_total 11002
telemt_me_reader_eof_total 11813
telemt_me_idle_close_by_peer_total 11811
telemt_me_route_drop_no_conn_total 162757
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355656
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11248
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10995
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 343924
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 5814343012 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 201449647168 (187.61 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 34
```