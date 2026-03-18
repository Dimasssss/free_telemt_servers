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

# Server Metrics 2026-03-18 17:46:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8473.3 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243827
telemt_connections_bad_total 15892
telemt_handshake_timeouts_total 6043
telemt_upstream_connect_attempt_total 1371
telemt_upstream_connect_success_total 1371
telemt_upstream_connect_attempts_per_request{bucket="1"} 1371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 910
telemt_me_reader_eof_total 938
telemt_me_idle_close_by_peer_total 938
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 113289
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206608
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1163
telemt_desync_full_logged_total 351
telemt_desync_suppressed_total 812
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 522
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 930
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 206519
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 2888408076 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 69498819036 (64.73 GB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 13301.7 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1361036
telemt_connections_bad_total 83015
telemt_connections_current 3485
telemt_connections_me_current 3485
telemt_handshake_timeouts_total 26600
telemt_upstream_connect_attempt_total 2308
telemt_upstream_connect_success_total 2296
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1619
telemt_me_reconnect_success_total 1605
telemt_me_reader_eof_total 1570
telemt_me_idle_close_by_peer_total 1569
telemt_me_route_drop_no_conn_total 1450371
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1183526
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3456
telemt_desync_full_logged_total 1102
telemt_desync_suppressed_total 2354
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1370
telemt_desync_frames_bucket_total{bucket="gt_10"} 1444
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1541
telemt_me_writer_restored_same_endpoint_total 1603
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1178834
telemt_user_connections_current{user="hello"} 3485
telemt_user_octets_from_client{user="hello"} 15265156504 (14.22 GB)
telemt_user_octets_to_client{user="hello"} 340674774380 (317.28 GB)
telemt_user_unique_ips_current{user="hello"} 1132
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 13229.8 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940486
telemt_connections_bad_total 74973
telemt_connections_current 3193
telemt_connections_me_current 3193
telemt_handshake_timeouts_total 21000
telemt_upstream_connect_attempt_total 1851
telemt_upstream_connect_success_total 1841
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1163
telemt_me_reconnect_success_total 1151
telemt_me_reader_eof_total 1217
telemt_me_idle_close_by_peer_total 1217
telemt_me_route_drop_no_conn_total 426421
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 778039
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3247
telemt_desync_full_logged_total 993
telemt_desync_suppressed_total 2254
telemt_desync_frames_bucket_total{bucket="1_2"} 809
telemt_desync_frames_bucket_total{bucket="3_10"} 1208
telemt_desync_frames_bucket_total{bucket="gt_10"} 1230
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1186
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 777674
telemt_user_connections_current{user="hello"} 3193
telemt_user_octets_from_client{user="hello"} 18912028764 (17.61 GB)
telemt_user_octets_to_client{user="hello"} 332757787144 (309.90 GB)
telemt_user_unique_ips_current{user="hello"} 1020
telemt_user_unique_ips_recent_window{user="hello"} 412
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 13944.3 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1395093
telemt_connections_bad_total 30095
telemt_connections_current 2976
telemt_connections_me_current 2976
telemt_handshake_timeouts_total 16130
telemt_upstream_connect_attempt_total 2156
telemt_upstream_connect_success_total 2140
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1415
telemt_me_reconnect_success_total 1397
telemt_me_reader_eof_total 1431
telemt_me_idle_close_by_peer_total 1430
telemt_me_route_drop_no_conn_total 2338352
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1247580
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4602
telemt_desync_full_logged_total 1171
telemt_desync_suppressed_total 3431
telemt_desync_frames_bucket_total{bucket="1_2"} 1071
telemt_desync_frames_bucket_total{bucket="3_10"} 2103
telemt_desync_frames_bucket_total{bucket="gt_10"} 1428
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1396
telemt_me_writer_restored_same_endpoint_total 1386
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1247495
telemt_user_connections_current{user="hello"} 2976
telemt_user_octets_from_client{user="hello"} 11686729952 (10.88 GB)
telemt_user_octets_to_client{user="hello"} 209098655756 (194.74 GB)
telemt_user_unique_ips_current{user="hello"} 896
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8459.2 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639513
telemt_connections_bad_total 120186
telemt_handshake_timeouts_total 6086
telemt_upstream_connect_attempt_total 1547
telemt_upstream_connect_success_total 1495
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 1547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 3119
telemt_me_reconnect_success_total 1030
telemt_me_reader_eof_total 1099
telemt_me_idle_close_by_peer_total 1099
telemt_me_route_drop_no_conn_total 251344
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466047
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1752
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 320
telemt_desync_frames_bucket_total{bucket="3_10"} 582
telemt_desync_frames_bucket_total{bucket="gt_10"} 850
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1109
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1004
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 465549
telemt_user_connections_current{user="hello"} 3074
telemt_user_octets_from_client{user="hello"} 7418080408 (6.91 GB)
telemt_user_octets_to_client{user="hello"} 197909943032 (184.32 GB)
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 13394.3 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245662
telemt_connections_bad_total 9218
telemt_connections_current 754
telemt_connections_me_current 754
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2661
telemt_upstream_connect_attempt_total 6398
telemt_upstream_connect_success_total 6385
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 331334
telemt_me_reconnect_success_total 1868
telemt_me_reader_eof_total 1851
telemt_me_idle_close_by_peer_total 1851
telemt_me_route_drop_no_conn_total 160156
telemt_me_route_drop_channel_closed_total 63
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217859
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 10
telemt_pool_stale_pick_total 670
telemt_me_writer_removed_unexpected_total 1810
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1857
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 221577
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 3288405581 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 45168308153 (42.07 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 12463.7 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755879
telemt_connections_bad_total 53990
telemt_connections_current 2790
telemt_connections_me_current 2790
telemt_handshake_timeouts_total 14027
telemt_upstream_connect_attempt_total 2169
telemt_upstream_connect_success_total 2168
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17033
telemt_me_reconnect_success_total 1519
telemt_me_reader_eof_total 1505
telemt_me_idle_close_by_peer_total 1505
telemt_me_route_drop_no_conn_total 410718
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633657
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2474
telemt_desync_full_logged_total 846
telemt_desync_suppressed_total 1628
telemt_desync_frames_bucket_total{bucket="1_2"} 623
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 980
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1484
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1458
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 632676
telemt_user_connections_current{user="hello"} 2790
telemt_user_octets_from_client{user="hello"} 12016548536 (11.19 GB)
telemt_user_octets_to_client{user="hello"} 313697101956 (292.15 GB)
telemt_user_unique_ips_current{user="hello"} 901
telemt_user_unique_ips_recent_window{user="hello"} 351
```