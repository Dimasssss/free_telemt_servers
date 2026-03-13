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

# Server Metrics 2026-03-13 13:33:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 108003.3 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444843
telemt_connections_bad_total 3214
telemt_handshake_timeouts_total 8472
telemt_upstream_connect_attempt_total 27273
telemt_upstream_connect_success_total 27145
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 27273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2408
telemt_me_reconnect_attempts_total 25280
telemt_me_reconnect_success_total 21753
telemt_me_reader_eof_total 23229
telemt_me_idle_close_by_peer_total 23228
telemt_me_route_drop_no_conn_total 142774
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388108
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1305
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 842
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 22091
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21737
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 387690
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 7056738948 (6.57 GB)
telemt_user_octets_to_client{user="hello"} 172536742632 (160.69 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 107897.1 (29h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207558
telemt_connections_bad_total 1680
telemt_handshake_timeouts_total 1518
telemt_upstream_connect_attempt_total 67775
telemt_upstream_connect_success_total 67050
telemt_upstream_connect_fail_total 725
telemt_upstream_connect_attempts_per_request{bucket="1"} 67775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 636
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 725
telemt_me_keepalive_timeout_total 1388
telemt_me_reconnect_attempts_total 102521
telemt_me_reconnect_success_total 25998
telemt_me_reader_eof_total 29149
telemt_me_idle_close_by_peer_total 29149
telemt_me_route_drop_no_conn_total 79758
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160552
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28613
telemt_me_refill_failed_total 2387
telemt_me_writer_restored_same_endpoint_total 25981
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2615
telemt_user_connections_total{user="hello"} 196006
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 2004592159 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 63843235491 (59.46 GB)
telemt_user_msgs_from_client{user="hello"} 534845
telemt_user_msgs_to_client{user="hello"} 3763978
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 107861.7 (29h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252582
telemt_connections_bad_total 2075
telemt_handshake_timeouts_total 9868
telemt_upstream_connect_attempt_total 29058
telemt_upstream_connect_success_total 29054
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2250
telemt_me_reconnect_attempts_total 24838
telemt_me_reconnect_success_total 23624
telemt_me_reader_eof_total 25308
telemt_me_idle_close_by_peer_total 25308
telemt_me_route_drop_no_conn_total 92214
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231534
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 23881
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23604
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 231450
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 9451366660 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 99915273800 (93.05 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 107836.2 (29h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350189
telemt_connections_bad_total 15034
telemt_handshake_timeouts_total 3415
telemt_upstream_connect_attempt_total 41008
telemt_upstream_connect_success_total 30898
telemt_upstream_connect_fail_total 10110
telemt_upstream_connect_attempts_per_request{bucket="1"} 41008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10110
telemt_me_keepalive_timeout_total 4128
telemt_me_reconnect_attempts_total 94945
telemt_me_reconnect_success_total 22462
telemt_me_reader_eof_total 25402
telemt_me_idle_close_by_peer_total 25395
telemt_me_route_drop_no_conn_total 125426
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301485
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1118
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 789
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 424
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 25012
telemt_me_refill_failed_total 2260
telemt_me_writer_restored_same_endpoint_total 22452
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2550
telemt_user_connections_total{user="hello"} 304396
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 6647401274 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 114352479737 (106.50 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 58007.7 (16h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86485
telemt_connections_bad_total 11446
telemt_handshake_timeouts_total 1203
telemt_upstream_connect_attempt_total 24416
telemt_upstream_connect_success_total 24219
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 24416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 999
telemt_me_reconnect_attempts_total 26314
telemt_me_reconnect_success_total 16395
telemt_me_reader_eof_total 17600
telemt_me_idle_close_by_peer_total 17600
telemt_me_route_drop_no_conn_total 25886
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66152
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 16846
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16377
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 71052
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 866919733 (826.76 MB)
telemt_user_octets_to_client{user="hello"} 20679611463 (19.26 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 107792.7 (29h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626377
telemt_connections_bad_total 17942
telemt_handshake_timeouts_total 17538
telemt_upstream_connect_attempt_total 22779
telemt_upstream_connect_success_total 22662
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 22779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 2505
telemt_me_reconnect_attempts_total 21930
telemt_me_reconnect_success_total 17306
telemt_me_reader_eof_total 18578
telemt_me_idle_close_by_peer_total 18575
telemt_me_route_drop_no_conn_total 305093
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 596665
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 17674
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17299
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 569696
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 9963346836 (9.28 GB)
telemt_user_octets_to_client{user="hello"} 303388205716 (282.55 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 72
```