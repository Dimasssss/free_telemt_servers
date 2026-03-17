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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 08:47:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 50502.5 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375786
telemt_connections_bad_total 3613
telemt_handshake_timeouts_total 11143
telemt_upstream_connect_attempt_total 13097
telemt_upstream_connect_success_total 12668
telemt_upstream_connect_fail_total 429
telemt_upstream_connect_attempts_per_request{bucket="1"} 13097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 429
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 9364
telemt_me_reconnect_success_total 7849
telemt_me_reader_eof_total 8341
telemt_me_idle_close_by_peer_total 8340
telemt_me_route_drop_no_conn_total 117528
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338152
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2595
telemt_desync_full_logged_total 730
telemt_desync_suppressed_total 1865
telemt_desync_frames_bucket_total{bucket="1_2"} 608
telemt_desync_frames_bucket_total{bucket="3_10"} 1222
telemt_desync_frames_bucket_total{bucket="gt_10"} 765
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8008
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 7827
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 340158
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 4772768579 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 136916013759 (127.51 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 50757.0 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204494
telemt_connections_bad_total 2372
telemt_handshake_timeouts_total 12283
telemt_upstream_connect_attempt_total 13761
telemt_upstream_connect_success_total 13580
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 13761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_reconnect_attempts_total 14357
telemt_me_reconnect_success_total 11059
telemt_me_reader_eof_total 11722
telemt_me_idle_close_by_peer_total 11722
telemt_me_route_drop_no_conn_total 74488
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179663
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 466
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11273
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11043
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 179671
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 2167364700 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 72518779612 (67.54 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 50529.7 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125888
telemt_connections_bad_total 7564
telemt_handshake_timeouts_total 7148
telemt_upstream_connect_attempt_total 13399
telemt_upstream_connect_success_total 13329
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 11730
telemt_me_reconnect_success_total 10768
telemt_me_reader_eof_total 11524
telemt_me_idle_close_by_peer_total 11524
telemt_me_route_drop_no_conn_total 39042
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102198
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 267
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10937
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 10757
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 102127
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 6627020152 (6.17 GB)
telemt_user_octets_to_client{user="hello"} 32284909372 (30.07 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 50588.9 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272644
telemt_connections_bad_total 6176
telemt_handshake_timeouts_total 10607
telemt_upstream_connect_attempt_total 11592
telemt_upstream_connect_success_total 11487
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 11592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9960
telemt_me_reconnect_success_total 8887
telemt_me_reader_eof_total 9459
telemt_me_idle_close_by_peer_total 9459
telemt_me_route_drop_no_conn_total 73628
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214006
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 449
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 283
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9058
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8879
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 213994
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 2274548974 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 91675305469 (85.38 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 50560.8 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154215
telemt_connections_bad_total 41473
telemt_handshake_timeouts_total 2705
telemt_upstream_connect_attempt_total 15484
telemt_upstream_connect_success_total 15277
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 15484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 19730
telemt_me_reconnect_success_total 12623
telemt_me_reader_eof_total 13402
telemt_me_idle_close_by_peer_total 13402
telemt_me_route_drop_no_conn_total 40536
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105200
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 298
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 224
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 12999
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 12615
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 105231
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 1700066163 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 48715791902 (45.37 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 50721.8 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371643
telemt_connections_bad_total 46359
telemt_handshake_timeouts_total 3744
telemt_upstream_connect_attempt_total 10438
telemt_upstream_connect_success_total 10381
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 10438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11723
telemt_me_reconnect_success_total 7844
telemt_me_reader_eof_total 8478
telemt_me_idle_close_by_peer_total 8478
telemt_me_route_drop_no_conn_total 257283
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378580
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 8082
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7830
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 300484
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 4198775816 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 174646426836 (162.65 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 38728.3 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3627
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 18954
telemt_upstream_connect_success_total 18940
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 18953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 17052
telemt_me_reconnect_success_total 16928
telemt_me_reader_eof_total 18464
telemt_me_idle_close_by_peer_total 18464
telemt_me_route_drop_no_conn_total 696
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3359
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 17085
telemt_me_writer_restored_same_endpoint_total 16928
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 3359
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 726561892 (692.90 MB)
telemt_user_octets_to_client{user="hello"} 21618026060 (20.13 GB)
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 5
```