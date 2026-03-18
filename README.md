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

# Server Metrics 2026-03-18 12:23:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 13376.6 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481651
telemt_connections_bad_total 6373
telemt_handshake_timeouts_total 13443
telemt_upstream_connect_attempt_total 65655
telemt_upstream_connect_success_total 64714
telemt_upstream_connect_fail_total 941
telemt_upstream_connect_attempts_per_request{bucket="1"} 65655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 941
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509868
telemt_me_reconnect_success_total 2064
telemt_me_reader_eof_total 2093
telemt_me_idle_close_by_peer_total 2091
telemt_me_route_drop_no_conn_total 286328
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366444
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1500
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 1007
telemt_desync_frames_bucket_total{bucket="1_2"} 436
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2105
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1959
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 424716
telemt_user_connections_current{user="hello"} 1753
telemt_user_octets_from_client{user="hello"} 5841382492 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 112363285001 (104.65 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 13407.6 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1341648
telemt_connections_bad_total 94184
telemt_handshake_timeouts_total 30863
telemt_upstream_connect_attempt_total 2299
telemt_upstream_connect_success_total 2287
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1606
telemt_me_reconnect_success_total 1562
telemt_me_reader_eof_total 1584
telemt_me_idle_close_by_peer_total 1583
telemt_me_route_drop_no_conn_total 1181773
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1156952
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3656
telemt_desync_full_logged_total 1069
telemt_desync_suppressed_total 2587
telemt_desync_frames_bucket_total{bucket="1_2"} 721
telemt_desync_frames_bucket_total{bucket="3_10"} 1479
telemt_desync_frames_bucket_total{bucket="gt_10"} 1456
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1566
telemt_me_writer_restored_same_endpoint_total 1561
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 1156044
telemt_user_connections_current{user="hello"} 4186
telemt_user_octets_from_client{user="hello"} 29334432540 (27.32 GB)
telemt_user_octets_to_client{user="hello"} 336565876036 (313.45 GB)
telemt_user_unique_ips_current{user="hello"} 1219
telemt_user_unique_ips_recent_window{user="hello"} 580
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 13322.9 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 948236
telemt_connections_bad_total 69986
telemt_handshake_timeouts_total 23453
telemt_upstream_connect_attempt_total 10744
telemt_upstream_connect_success_total 10744
telemt_upstream_connect_attempts_per_request{bucket="1"} 10744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607518
telemt_me_reconnect_success_total 1825
telemt_me_reader_eof_total 1842
telemt_me_idle_close_by_peer_total 1841
telemt_me_route_drop_no_conn_total 409356
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2018
telemt_desync_full_logged_total 698
telemt_desync_suppressed_total 1320
telemt_desync_frames_bucket_total{bucket="1_2"} 533
telemt_desync_frames_bucket_total{bucket="3_10"} 751
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1834
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1790
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 724234
telemt_user_connections_current{user="hello"} 3320
telemt_user_octets_from_client{user="hello"} 8665683419 (8.07 GB)
telemt_user_octets_to_client{user="hello"} 302946903948 (282.14 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 965
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 13352.8 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1489048
telemt_connections_bad_total 22790
telemt_handshake_timeouts_total 161427
telemt_upstream_connect_attempt_total 12330
telemt_upstream_connect_success_total 12153
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 12330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2827084
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 1636
telemt_me_idle_close_by_peer_total 1636
telemt_me_route_drop_no_conn_total 2135885
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1176554
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2475
telemt_desync_full_logged_total 804
telemt_desync_suppressed_total 1671
telemt_desync_frames_bucket_total{bucket="1_2"} 612
telemt_desync_frames_bucket_total{bucket="3_10"} 1007
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_me_writer_removed_unexpected_total 1680
telemt_me_refill_failed_total 100047
telemt_me_writer_restored_same_endpoint_total 1083
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 502
telemt_user_connections_total{user="hello"} 1195207
telemt_user_connections_current{user="hello"} 3302
telemt_user_octets_from_client{user="hello"} 12550423322 (11.69 GB)
telemt_user_octets_to_client{user="hello"} 202207147721 (188.32 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 957
telemt_user_unique_ips_recent_window{user="hello"} 512
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 13247.6 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 983806
telemt_connections_bad_total 41189
telemt_handshake_timeouts_total 17126
telemt_upstream_connect_attempt_total 11755
telemt_upstream_connect_success_total 11754
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983516
telemt_me_reconnect_success_total 1552
telemt_me_reader_eof_total 1549
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 611759
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 838477
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2854
telemt_desync_full_logged_total 947
telemt_desync_suppressed_total 1907
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 1124
telemt_desync_frames_bucket_total{bucket="gt_10"} 1317
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1526
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1437
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 838719
telemt_user_connections_current{user="hello"} 3419
telemt_user_octets_from_client{user="hello"} 12670696197 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 322470572245 (300.32 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 13132.8 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277532
telemt_connections_bad_total 25270
telemt_handshake_timeouts_total 2176
telemt_upstream_connect_attempt_total 2617
telemt_upstream_connect_success_total 2617
telemt_upstream_connect_attempts_per_request{bucket="1"} 2617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1377
telemt_me_reconnect_attempts_total 4341
telemt_me_reconnect_success_total 1893
telemt_me_reader_eof_total 2007
telemt_me_idle_close_by_peer_total 2006
telemt_me_route_drop_no_conn_total 139866
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239150
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 616
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1985
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1885
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 229448
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 4187445576 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 51725135680 (48.17 GB)
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 13203.8 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796718
telemt_connections_bad_total 109827
telemt_handshake_timeouts_total 17326
telemt_upstream_connect_attempt_total 2373
telemt_upstream_connect_success_total 2349
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1658
telemt_me_reconnect_success_total 1631
telemt_me_reader_eof_total 1667
telemt_me_idle_close_by_peer_total 1667
telemt_me_route_drop_no_conn_total 310113
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606618
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2221
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1462
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 782
telemt_desync_frames_bucket_total{bucket="gt_10"} 1066
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1637
telemt_me_writer_restored_same_endpoint_total 1621
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 606143
telemt_user_connections_current{user="hello"} 3109
telemt_user_octets_from_client{user="hello"} 13333959072 (12.42 GB)
telemt_user_octets_to_client{user="hello"} 310906600604 (289.55 GB)
telemt_user_unique_ips_current{user="hello"} 936
telemt_user_unique_ips_recent_window{user="hello"} 433
```