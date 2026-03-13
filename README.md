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

# Server Metrics 2026-03-13 19:35:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 129711.3 (36h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550301
telemt_connections_bad_total 13322
telemt_handshake_timeouts_total 12456
telemt_upstream_connect_attempt_total 32804
telemt_upstream_connect_success_total 32637
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 32804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5046
telemt_me_reconnect_attempts_total 30396
telemt_me_reconnect_success_total 25745
telemt_me_reader_eof_total 27494
telemt_me_idle_close_by_peer_total 27493
telemt_me_route_drop_no_conn_total 181344
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475132
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 26178
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25729
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 475027
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 8775538394 (8.17 GB)
telemt_user_octets_to_client{user="hello"} 226976070652 (211.39 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 129603.7 (36h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275165
telemt_connections_bad_total 2098
telemt_handshake_timeouts_total 1875
telemt_upstream_connect_attempt_total 126407
telemt_upstream_connect_success_total 125472
telemt_upstream_connect_fail_total 935
telemt_upstream_connect_attempts_per_request{bucket="1"} 126407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 935
telemt_me_keepalive_timeout_total 3601
telemt_me_reconnect_attempts_total 135192
telemt_me_reconnect_success_total 26285
telemt_me_reader_eof_total 30424
telemt_me_idle_close_by_peer_total 30424
telemt_me_route_drop_no_conn_total 83557
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168199
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 32
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
telemt_me_writer_removed_unexpected_total 29931
telemt_me_refill_failed_total 3398
telemt_me_writer_restored_same_endpoint_total 26268
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3646
telemt_user_connections_total{user="hello"} 260724
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2691575660 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 78558592655 (73.16 GB)
telemt_user_msgs_from_client{user="hello"} 1459412
telemt_user_msgs_to_client{user="hello"} 8134345
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 129567.3 (35h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322376
telemt_connections_bad_total 2632
telemt_handshake_timeouts_total 21996
telemt_upstream_connect_attempt_total 34384
telemt_upstream_connect_success_total 34379
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18431
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2786
telemt_me_reconnect_attempts_total 29121
telemt_me_reconnect_success_total 27883
telemt_me_reader_eof_total 29915
telemt_me_idle_close_by_peer_total 29915
telemt_me_route_drop_no_conn_total 115490
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286526
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 28201
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27863
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 286435
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 11746650708 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 120312287280 (112.05 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 129542.8 (35h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427302
telemt_connections_bad_total 15198
telemt_handshake_timeouts_total 4128
telemt_upstream_connect_attempt_total 62221
telemt_upstream_connect_success_total 51940
telemt_upstream_connect_fail_total 10281
telemt_upstream_connect_attempts_per_request{bucket="1"} 62221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 295
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10281
telemt_me_keepalive_timeout_total 4721
telemt_me_reconnect_attempts_total 117079
telemt_me_reconnect_success_total 26457
telemt_me_reader_eof_total 30053
telemt_me_idle_close_by_peer_total 30046
telemt_me_route_drop_no_conn_total 147853
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358608
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1443
telemt_desync_full_logged_total 430
telemt_desync_suppressed_total 1013
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 551
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 29623
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 26447
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3166
telemt_user_connections_total{user="hello"} 377473
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 8555738903 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 135656301108 (126.34 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 79714.5 (22h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134844
telemt_connections_bad_total 16724
telemt_handshake_timeouts_total 1424
telemt_upstream_connect_attempt_total 30597
telemt_upstream_connect_success_total 30306
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 30597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 1246
telemt_me_reconnect_attempts_total 34811
telemt_me_reconnect_success_total 21420
telemt_me_reader_eof_total 22949
telemt_me_idle_close_by_peer_total 22949
telemt_me_route_drop_no_conn_total 42117
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107414
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 594
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 22037
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21402
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 112309
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 1307640077 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 43331476731 (40.36 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 129499.1 (35h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793652
telemt_connections_bad_total 24789
telemt_handshake_timeouts_total 24875
telemt_upstream_connect_attempt_total 26690
telemt_upstream_connect_success_total 26550
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 26690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 3051
telemt_me_reconnect_attempts_total 24784
telemt_me_reconnect_success_total 20138
telemt_me_reader_eof_total 21609
telemt_me_idle_close_by_peer_total 21606
telemt_me_route_drop_no_conn_total 377274
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744020
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20552
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20131
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 716890
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 12399396784 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 352586320236 (328.37 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 59
```