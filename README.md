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

# Server Metrics 2026-03-19 17:31:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 820.6 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32206
telemt_connections_bad_total 717
telemt_connections_current 1709
telemt_connections_me_current 1709
telemt_handshake_timeouts_total 408
telemt_upstream_connect_attempt_total 118
telemt_upstream_connect_success_total 116
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 50
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 33
telemt_me_idle_close_by_peer_total 33
telemt_me_route_drop_no_conn_total 8780
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28064
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 126
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 55
telemt_me_writer_restored_same_endpoint_total 37
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 28064
telemt_user_connections_current{user="hello"} 1709
telemt_user_octets_from_client{user="hello"} 269161796 (256.69 MB)
telemt_user_octets_to_client{user="hello"} 8144887992 (7.59 GB)
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 17276.4 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1770525
telemt_connections_bad_total 89091
telemt_connections_current 3878
telemt_connections_me_current 3878
telemt_handshake_timeouts_total 33442
telemt_upstream_connect_attempt_total 4231
telemt_upstream_connect_success_total 4177
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6251
telemt_me_reconnect_success_total 2028
telemt_me_reader_eof_total 2193
telemt_me_idle_close_by_peer_total 2193
telemt_me_route_drop_no_conn_total 1053582
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1459055
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5654
telemt_desync_full_logged_total 1750
telemt_desync_suppressed_total 3904
telemt_desync_frames_bucket_total{bucket="1_2"} 1117
telemt_desync_frames_bucket_total{bucket="3_10"} 2226
telemt_desync_frames_bucket_total{bucket="gt_10"} 2311
telemt_pool_swap_total 11
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2169
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1973
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 1459057
telemt_user_connections_current{user="hello"} 3878
telemt_user_octets_from_client{user="hello"} 21771881246 (20.28 GB)
telemt_user_octets_to_client{user="hello"} 460500176030 (428.87 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1302
telemt_user_unique_ips_recent_window{user="hello"} 583
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 17254.4 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1650811
telemt_connections_bad_total 204535
telemt_connections_current 2934
telemt_connections_me_current 2934
telemt_handshake_timeouts_total 17276
telemt_upstream_connect_attempt_total 2793
telemt_upstream_connect_success_total 2774
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2770
telemt_me_reconnect_success_total 1852
telemt_me_reader_eof_total 1873
telemt_me_idle_close_by_peer_total 1872
telemt_me_route_drop_no_conn_total 1516455
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1247448
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3952
telemt_desync_full_logged_total 1158
telemt_desync_suppressed_total 2794
telemt_desync_frames_bucket_total{bucket="1_2"} 1053
telemt_desync_frames_bucket_total{bucket="3_10"} 1475
telemt_desync_frames_bucket_total{bucket="gt_10"} 1424
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 1839
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1851
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1244685
telemt_user_connections_current{user="hello"} 2934
telemt_user_octets_from_client{user="hello"} 15046835368 (14.01 GB)
telemt_user_octets_to_client{user="hello"} 370616557748 (345.16 GB)
telemt_user_unique_ips_current{user="hello"} 1021
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 17242.0 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1409381
telemt_connections_bad_total 57109
telemt_connections_current 3087
telemt_connections_me_current 3087
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 20813
telemt_upstream_connect_attempt_total 19947
telemt_upstream_connect_success_total 19027
telemt_upstream_connect_fail_total 919
telemt_upstream_connect_attempts_per_request{bucket="1"} 19946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 919
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4436
telemt_me_reconnect_success_total 2169
telemt_me_reader_eof_total 2250
telemt_me_idle_close_by_peer_total 2249
telemt_me_route_drop_no_conn_total 1070194
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1208912
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5027
telemt_desync_full_logged_total 1571
telemt_desync_suppressed_total 3456
telemt_desync_frames_bucket_total{bucket="1_2"} 1337
telemt_desync_frames_bucket_total{bucket="3_10"} 1856
telemt_desync_frames_bucket_total{bucket="gt_10"} 1834
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_removed_unexpected_total 2499
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2165
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 1224220
telemt_user_connections_current{user="hello"} 3087
telemt_user_octets_from_client{user="hello"} 23442916469 (21.83 GB)
telemt_user_octets_to_client{user="hello"} 281794843678 (262.44 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 1024
telemt_user_unique_ips_recent_window{user="hello"} 445
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 70965.2 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5101326
telemt_connections_bad_total 887812
telemt_connections_current 3694
telemt_connections_me_current 3694
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 96072
telemt_upstream_connect_attempt_total 64388
telemt_upstream_connect_success_total 61897
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1037
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74575
telemt_me_reconnect_success_total 9170
telemt_me_reader_eof_total 9656
telemt_me_idle_close_by_peer_total 9653
telemt_me_route_drop_no_conn_total 2406392
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3576561
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
telemt_desync_total 15642
telemt_desync_full_logged_total 4757
telemt_desync_suppressed_total 10885
telemt_desync_frames_bucket_total{bucket="1_2"} 2555
telemt_desync_frames_bucket_total{bucket="3_10"} 6565
telemt_desync_frames_bucket_total{bucket="gt_10"} 6522
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 9405
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9146
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 3624695
telemt_user_connections_current{user="hello"} 3694
telemt_user_octets_from_client{user="hello"} 56730974655 (52.83 GB)
telemt_user_octets_to_client{user="hello"} 1317718761548 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1188
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 17210.3 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355996
telemt_connections_bad_total 27255
telemt_connections_current 951
telemt_connections_me_current 951
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 7723
telemt_upstream_connect_attempt_total 6030
telemt_upstream_connect_success_total 5893
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 6030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 2475
telemt_me_reconnect_success_total 2435
telemt_me_reader_eof_total 2482
telemt_me_idle_close_by_peer_total 2482
telemt_me_route_drop_no_conn_total 214253
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300022
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 941
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 651
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 377
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 10
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 2427
telemt_me_writer_restored_same_endpoint_total 2426
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 302597
telemt_user_connections_current{user="hello"} 951
telemt_user_octets_from_client{user="hello"} 4176474100 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 78233697822 (72.86 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 17206.4 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158764
telemt_connections_bad_total 79747
telemt_connections_current 3205
telemt_connections_me_current 3205
telemt_handshake_timeouts_total 19453
telemt_upstream_connect_attempt_total 2916
telemt_upstream_connect_success_total 2893
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 1990
telemt_me_reconnect_success_total 1965
telemt_me_reader_eof_total 2052
telemt_me_idle_close_by_peer_total 2052
telemt_me_route_drop_no_conn_total 455963
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993185
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5539
telemt_desync_full_logged_total 1673
telemt_desync_suppressed_total 3866
telemt_desync_frames_bucket_total{bucket="1_2"} 1118
telemt_desync_frames_bucket_total{bucket="3_10"} 1906
telemt_desync_frames_bucket_total{bucket="gt_10"} 2515
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 2006
telemt_me_writer_restored_same_endpoint_total 1948
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 992734
telemt_user_connections_current{user="hello"} 3205
telemt_user_octets_from_client{user="hello"} 15150443764 (14.11 GB)
telemt_user_octets_to_client{user="hello"} 428082046620 (398.68 GB)
telemt_user_unique_ips_current{user="hello"} 1054
telemt_user_unique_ips_recent_window{user="hello"} 418
```