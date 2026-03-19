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

# Server Metrics 2026-03-19 18:27:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 4201.1 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132843
telemt_connections_bad_total 4186
telemt_connections_current 1470
telemt_connections_me_current 1470
telemt_handshake_timeouts_total 1396
telemt_upstream_connect_attempt_total 626
telemt_upstream_connect_success_total 617
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 378
telemt_me_reconnect_success_total 376
telemt_me_reader_eof_total 378
telemt_me_idle_close_by_peer_total 378
telemt_me_route_drop_no_conn_total 43271
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111790
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 495
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 389
telemt_me_writer_restored_same_endpoint_total 363
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 112030
telemt_user_connections_current{user="hello"} 1470
telemt_user_octets_from_client{user="hello"} 1802512220 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 37488560296 (34.91 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 20657.1 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2043913
telemt_connections_bad_total 98455
telemt_connections_current 3733
telemt_connections_me_current 3733
telemt_handshake_timeouts_total 38327
telemt_upstream_connect_attempt_total 4723
telemt_upstream_connect_success_total 4663
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 4723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6608
telemt_me_reconnect_success_total 2383
telemt_me_reader_eof_total 2565
telemt_me_idle_close_by_peer_total 2565
telemt_me_route_drop_no_conn_total 1164411
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1702912
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6886
telemt_desync_full_logged_total 2188
telemt_desync_suppressed_total 4698
telemt_desync_frames_bucket_total{bucket="1_2"} 1308
telemt_desync_frames_bucket_total{bucket="3_10"} 2732
telemt_desync_frames_bucket_total{bucket="gt_10"} 2846
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2529
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2328
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1702881
telemt_user_connections_current{user="hello"} 3733
telemt_user_octets_from_client{user="hello"} 24849870090 (23.14 GB)
telemt_user_octets_to_client{user="hello"} 556169743454 (517.97 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1276
telemt_user_unique_ips_recent_window{user="hello"} 512
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 20635.0 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1871155
telemt_connections_bad_total 221440
telemt_connections_current 2703
telemt_connections_me_current 2703
telemt_handshake_timeouts_total 20675
telemt_upstream_connect_attempt_total 3237
telemt_upstream_connect_success_total 3215
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3082
telemt_me_reconnect_success_total 2164
telemt_me_reader_eof_total 2206
telemt_me_idle_close_by_peer_total 2205
telemt_me_route_drop_no_conn_total 1597769
telemt_me_route_drop_channel_closed_total 100
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1423103
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4611
telemt_desync_full_logged_total 1383
telemt_desync_suppressed_total 3228
telemt_desync_frames_bucket_total{bucket="1_2"} 1191
telemt_desync_frames_bucket_total{bucket="3_10"} 1738
telemt_desync_frames_bucket_total{bucket="gt_10"} 1682
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 47
telemt_me_writer_removed_unexpected_total 2157
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2163
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1420093
telemt_user_connections_current{user="hello"} 2703
telemt_user_octets_from_client{user="hello"} 18390468416 (17.13 GB)
telemt_user_octets_to_client{user="hello"} 452845571852 (421.75 GB)
telemt_user_unique_ips_current{user="hello"} 923
telemt_user_unique_ips_recent_window{user="hello"} 343
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 20622.7 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1751524
telemt_connections_bad_total 59544
telemt_connections_current 2489
telemt_connections_me_current 2489
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 23658
telemt_upstream_connect_attempt_total 25226
telemt_upstream_connect_success_total 24047
telemt_upstream_connect_fail_total 1179
telemt_upstream_connect_attempts_per_request{bucket="1"} 25226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1179
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4941
telemt_me_reconnect_success_total 2568
telemt_me_reader_eof_total 2653
telemt_me_idle_close_by_peer_total 2652
telemt_me_route_drop_no_conn_total 1538232
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1511060
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5926
telemt_desync_full_logged_total 1851
telemt_desync_suppressed_total 4075
telemt_desync_frames_bucket_total{bucket="1_2"} 1571
telemt_desync_frames_bucket_total{bucket="3_10"} 2184
telemt_desync_frames_bucket_total{bucket="gt_10"} 2171
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 2976
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2564
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 1530398
telemt_user_connections_current{user="hello"} 2489
telemt_user_octets_from_client{user="hello"} 26710454989 (24.88 GB)
telemt_user_octets_to_client{user="hello"} 331628626081 (308.85 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 898
telemt_user_unique_ips_recent_window{user="hello"} 355
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 74347.4 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5436311
telemt_connections_bad_total 1004040
telemt_connections_current 3231
telemt_connections_me_current 3231
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 99265
telemt_upstream_connect_attempt_total 64868
telemt_upstream_connect_success_total 62375
telemt_upstream_connect_fail_total 2493
telemt_upstream_connect_attempts_per_request{bucket="1"} 64868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1047
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2493
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74879
telemt_me_reconnect_success_total 9470
telemt_me_reader_eof_total 9981
telemt_me_idle_close_by_peer_total 9978
telemt_me_route_drop_no_conn_total 2496260
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3768180
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
telemt_desync_total 16395
telemt_desync_full_logged_total 5031
telemt_desync_suppressed_total 11364
telemt_desync_frames_bucket_total{bucket="1_2"} 2694
telemt_desync_frames_bucket_total{bucket="3_10"} 6849
telemt_desync_frames_bucket_total{bucket="gt_10"} 6852
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 9713
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9446
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 3816298
telemt_user_connections_current{user="hello"} 3231
telemt_user_octets_from_client{user="hello"} 59629417263 (55.53 GB)
telemt_user_octets_to_client{user="hello"} 1402009181584 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1146
telemt_user_unique_ips_recent_window{user="hello"} 451
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 20586.5 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489764
telemt_connections_bad_total 33787
telemt_connections_current 584
telemt_connections_me_current 584
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10052
telemt_upstream_connect_attempt_total 7039
telemt_upstream_connect_success_total 6842
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 2855
telemt_me_reconnect_success_total 2799
telemt_me_reader_eof_total 2867
telemt_me_idle_close_by_peer_total 2866
telemt_me_route_drop_no_conn_total 353476
telemt_me_route_drop_channel_closed_total 123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386811
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
telemt_desync_total 1034
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 706
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 452
telemt_pool_swap_total 12
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 131
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2817
telemt_me_writer_restored_same_endpoint_total 2790
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 405468
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 4702073112 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 85329044042 (79.47 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 20587.2 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1356920
telemt_connections_bad_total 86683
telemt_connections_current 3090
telemt_connections_me_current 3090
telemt_handshake_timeouts_total 24304
telemt_upstream_connect_attempt_total 3381
telemt_upstream_connect_success_total 3355
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2323
telemt_me_reconnect_success_total 2298
telemt_me_reader_eof_total 2408
telemt_me_idle_close_by_peer_total 2408
telemt_me_route_drop_no_conn_total 524857
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1172345
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6256
telemt_desync_full_logged_total 1908
telemt_desync_suppressed_total 4348
telemt_desync_frames_bucket_total{bucket="1_2"} 1223
telemt_desync_frames_bucket_total{bucket="3_10"} 2169
telemt_desync_frames_bucket_total{bucket="gt_10"} 2864
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 2345
telemt_me_writer_restored_same_endpoint_total 2281
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1171635
telemt_user_connections_current{user="hello"} 3090
telemt_user_octets_from_client{user="hello"} 18176521692 (16.93 GB)
telemt_user_octets_to_client{user="hello"} 516058076332 (480.62 GB)
telemt_user_unique_ips_current{user="hello"} 968
telemt_user_unique_ips_recent_window{user="hello"} 387
```