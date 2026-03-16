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

# Server Metrics 2026-03-16 11:49:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 135281.5 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738085
telemt_connections_bad_total 54001
telemt_handshake_timeouts_total 23564
telemt_upstream_connect_attempt_total 31247
telemt_upstream_connect_success_total 31097
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 31247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 38596
telemt_me_reconnect_success_total 24368
telemt_me_reader_eof_total 26310
telemt_me_idle_close_by_peer_total 26310
telemt_me_route_drop_no_conn_total 603445
telemt_me_route_drop_channel_closed_total 92
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680371
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3180
telemt_desync_full_logged_total 1211
telemt_desync_suppressed_total 1969
telemt_desync_frames_bucket_total{bucket="1_2"} 686
telemt_desync_frames_bucket_total{bucket="3_10"} 1280
telemt_desync_frames_bucket_total{bucket="gt_10"} 1214
telemt_pool_swap_total 124
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25077
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24333
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 709
telemt_user_connections_total{user="hello"} 616889
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 11831568572 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 359745184244 (335.04 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 135288.4 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301683
telemt_connections_bad_total 3814
telemt_handshake_timeouts_total 19237
telemt_upstream_connect_attempt_total 36344
telemt_upstream_connect_success_total 36237
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 36344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19744
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 829
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 41567
telemt_me_reconnect_success_total 28877
telemt_me_reader_eof_total 30994
telemt_me_idle_close_by_peer_total 30993
telemt_me_route_drop_no_conn_total 144543
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267252
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 29682
telemt_me_refill_failed_total 387
telemt_me_writer_restored_same_endpoint_total 28861
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 805
telemt_user_connections_total{user="hello"} 266953
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 5468132109 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 133895024824 (124.70 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 135280.6 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294591
telemt_connections_bad_total 5936
telemt_handshake_timeouts_total 8313
telemt_upstream_connect_attempt_total 37545
telemt_upstream_connect_success_total 37537
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38163
telemt_me_reconnect_success_total 30728
telemt_me_reader_eof_total 33002
telemt_me_idle_close_by_peer_total 33001
telemt_me_route_drop_no_conn_total 100711
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240663
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 31272
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30720
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 240262
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 18841609709 (17.55 GB)
telemt_user_octets_to_client{user="hello"} 128496821032 (119.67 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 135280.3 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442647
telemt_connections_bad_total 1459
telemt_handshake_timeouts_total 4075
telemt_upstream_connect_attempt_total 31299
telemt_upstream_connect_success_total 31255
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 31299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 29501
telemt_me_reconnect_success_total 24499
telemt_me_reader_eof_total 26238
telemt_me_idle_close_by_peer_total 26237
telemt_me_route_drop_no_conn_total 150491
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409216
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1494
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 993
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 24985
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24488
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 409074
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 6461526706 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 157908585316 (147.06 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 110351.6 (30h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275550
telemt_connections_bad_total 48404
telemt_handshake_timeouts_total 4486
telemt_upstream_connect_attempt_total 31507
telemt_upstream_connect_success_total 31336
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 31507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 121276
telemt_me_reconnect_success_total 25672
telemt_me_reader_eof_total 27266
telemt_me_idle_close_by_peer_total 27266
telemt_me_route_drop_no_conn_total 83290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214215
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 700
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 25929
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 25568
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 213834
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 2802429145 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 97137559323 (90.47 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 135279.9 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959854
telemt_connections_bad_total 75127
telemt_handshake_timeouts_total 11481
telemt_upstream_connect_attempt_total 28636
telemt_upstream_connect_success_total 28485
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 28636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 24337
telemt_me_reconnect_success_total 21717
telemt_me_reader_eof_total 23179
telemt_me_idle_close_by_peer_total 23178
telemt_me_route_drop_no_conn_total 702140
telemt_me_route_drop_channel_closed_total 130
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940214
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 585
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22061
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21690
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 798814
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 17378165196 (16.18 GB)
telemt_user_octets_to_client{user="hello"} 458580541684 (427.09 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 106
```