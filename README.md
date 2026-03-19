# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 18:48:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 5427.2 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174526
telemt_connections_bad_total 6152
telemt_connections_current 1413
telemt_connections_me_current 1413
telemt_handshake_timeouts_total 1893
telemt_upstream_connect_attempt_total 783
telemt_upstream_connect_success_total 770
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 485
telemt_me_reconnect_success_total 481
telemt_me_reader_eof_total 491
telemt_me_idle_close_by_peer_total 491
telemt_me_route_drop_no_conn_total 54672
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140147
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 644
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 433
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 497
telemt_me_writer_restored_same_endpoint_total 468
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 140356
telemt_user_connections_current{user="hello"} 1413
telemt_user_octets_from_client{user="hello"} 2139372772 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 47104916552 (43.87 GB)
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 21883.1 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2136623
telemt_connections_bad_total 100092
telemt_connections_current 3662
telemt_connections_me_current 3662
telemt_handshake_timeouts_total 39900
telemt_upstream_connect_attempt_total 4946
telemt_upstream_connect_success_total 4880
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6738
telemt_me_reconnect_success_total 2513
telemt_me_reader_eof_total 2712
telemt_me_idle_close_by_peer_total 2712
telemt_me_route_drop_no_conn_total 1200586
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1788615
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7283
telemt_desync_full_logged_total 2319
telemt_desync_suppressed_total 4964
telemt_desync_frames_bucket_total{bucket="1_2"} 1374
telemt_desync_frames_bucket_total{bucket="3_10"} 2882
telemt_desync_frames_bucket_total{bucket="gt_10"} 3027
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2659
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2458
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1788561
telemt_user_connections_current{user="hello"} 3662
telemt_user_octets_from_client{user="hello"} 25912972286 (24.13 GB)
telemt_user_octets_to_client{user="hello"} 589952146738 (549.44 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1277
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 21861.2 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1948038
telemt_connections_bad_total 229939
telemt_connections_current 2713
telemt_connections_me_current 2713
telemt_handshake_timeouts_total 22375
telemt_upstream_connect_attempt_total 3452
telemt_upstream_connect_success_total 3427
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3206
telemt_me_reconnect_success_total 2288
telemt_me_reader_eof_total 2341
telemt_me_idle_close_by_peer_total 2340
telemt_me_route_drop_no_conn_total 1697732
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1484279
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5051
telemt_desync_full_logged_total 1500
telemt_desync_suppressed_total 3551
telemt_desync_frames_bucket_total{bucket="1_2"} 1288
telemt_desync_frames_bucket_total{bucket="3_10"} 1905
telemt_desync_frames_bucket_total{bucket="gt_10"} 1858
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 2284
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2287
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1480762
telemt_user_connections_current{user="hello"} 2713
telemt_user_octets_from_client{user="hello"} 19540578176 (18.20 GB)
telemt_user_octets_to_client{user="hello"} 478561822284 (445.70 GB)
telemt_user_unique_ips_current{user="hello"} 952
telemt_user_unique_ips_recent_window{user="hello"} 340
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 21848.8 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1826672
telemt_connections_bad_total 61024
telemt_connections_current 2518
telemt_connections_me_current 2518
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 24436
telemt_upstream_connect_attempt_total 25459
telemt_upstream_connect_success_total 24268
telemt_upstream_connect_fail_total 1191
telemt_upstream_connect_attempts_per_request{bucket="1"} 25459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1191
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5083
telemt_me_reconnect_success_total 2703
telemt_me_reader_eof_total 2798
telemt_me_idle_close_by_peer_total 2797
telemt_me_route_drop_no_conn_total 1591794
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1576413
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6203
telemt_desync_full_logged_total 1924
telemt_desync_suppressed_total 4279
telemt_desync_frames_bucket_total{bucket="1_2"} 1616
telemt_desync_frames_bucket_total{bucket="3_10"} 2273
telemt_desync_frames_bucket_total{bucket="gt_10"} 2314
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3117
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2699
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 1595752
telemt_user_connections_current{user="hello"} 2518
telemt_user_octets_from_client{user="hello"} 27384348261 (25.50 GB)
telemt_user_octets_to_client{user="hello"} 351575263565 (327.43 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 928
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 75572.0 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5518436
telemt_connections_bad_total 1007598
telemt_connections_current 3241
telemt_connections_me_current 3241
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 100765
telemt_upstream_connect_attempt_total 65001
telemt_upstream_connect_success_total 62508
telemt_upstream_connect_fail_total 2493
telemt_upstream_connect_attempts_per_request{bucket="1"} 65001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1049
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2493
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74969
telemt_me_reconnect_success_total 9559
telemt_me_reader_eof_total 10078
telemt_me_idle_close_by_peer_total 10075
telemt_me_route_drop_no_conn_total 2535145
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3836390
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16834
telemt_desync_full_logged_total 5160
telemt_desync_suppressed_total 11674
telemt_desync_frames_bucket_total{bucket="1_2"} 2806
telemt_desync_frames_bucket_total{bucket="3_10"} 6994
telemt_desync_frames_bucket_total{bucket="gt_10"} 7034
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 9806
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9535
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 3884517
telemt_user_connections_current{user="hello"} 3241
telemt_user_octets_from_client{user="hello"} 60918175819 (56.73 GB)
telemt_user_octets_to_client{user="hello"} 1429646147716 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1130
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 21812.8 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507383
telemt_connections_bad_total 35779
telemt_connections_current 636
telemt_connections_me_current 636
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10359
telemt_upstream_connect_attempt_total 7259
telemt_upstream_connect_success_total 7062
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4059
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 2989
telemt_me_reconnect_success_total 2932
telemt_me_reader_eof_total 3013
telemt_me_idle_close_by_peer_total 3012
telemt_me_route_drop_no_conn_total 359658
telemt_me_route_drop_channel_closed_total 125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401418
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1068
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 729
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 435
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 14
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 131
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2952
telemt_me_writer_restored_same_endpoint_total 2923
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 420064
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 4806494100 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 87911856138 (81.87 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 21813.4 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1423305
telemt_connections_bad_total 88485
telemt_connections_current 3099
telemt_connections_me_current 3099
telemt_handshake_timeouts_total 24829
telemt_upstream_connect_attempt_total 3616
telemt_upstream_connect_success_total 3589
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 2471
telemt_me_reconnect_success_total 2444
telemt_me_reader_eof_total 2564
telemt_me_idle_close_by_peer_total 2564
telemt_me_route_drop_no_conn_total 547194
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1232578
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6545
telemt_desync_full_logged_total 2012
telemt_desync_suppressed_total 4533
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 2295
telemt_desync_frames_bucket_total{bucket="gt_10"} 2996
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2494
telemt_me_writer_restored_same_endpoint_total 2427
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 1231870
telemt_user_connections_current{user="hello"} 3099
telemt_user_octets_from_client{user="hello"} 19553814184 (18.21 GB)
telemt_user_octets_to_client{user="hello"} 546882452724 (509.32 GB)
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 357
```