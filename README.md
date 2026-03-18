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

# Server Metrics 2026-03-18 18:48:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12162.5 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328557
telemt_connections_bad_total 19928
telemt_handshake_timeouts_total 7479
telemt_upstream_connect_attempt_total 2021
telemt_upstream_connect_success_total 2021
telemt_upstream_connect_attempts_per_request{bucket="1"} 2021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1390
telemt_me_reconnect_success_total 1384
telemt_me_reader_eof_total 1437
telemt_me_idle_close_by_peer_total 1437
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 145081
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282543
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1676
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1410
telemt_me_writer_restored_same_endpoint_total 1369
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 282425
telemt_user_connections_current{user="hello"} 1222
telemt_user_octets_from_client{user="hello"} 5337306224 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 94714726308 (88.21 GB)
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 16990.6 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1654741
telemt_connections_bad_total 109036
telemt_connections_current 4032
telemt_connections_me_current 4032
telemt_handshake_timeouts_total 30610
telemt_upstream_connect_attempt_total 2768
telemt_upstream_connect_success_total 2754
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1905
telemt_me_reconnect_success_total 1889
telemt_me_reader_eof_total 1880
telemt_me_idle_close_by_peer_total 1879
telemt_me_route_drop_no_conn_total 1579437
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1433300
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4636
telemt_desync_full_logged_total 1488
telemt_desync_suppressed_total 3148
telemt_desync_frames_bucket_total{bucket="1_2"} 802
telemt_desync_frames_bucket_total{bucket="3_10"} 1826
telemt_desync_frames_bucket_total{bucket="gt_10"} 2008
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1836
telemt_me_writer_restored_same_endpoint_total 1887
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1428467
telemt_user_connections_current{user="hello"} 4032
telemt_user_octets_from_client{user="hello"} 18891982848 (17.59 GB)
telemt_user_octets_to_client{user="hello"} 446419263540 (415.76 GB)
telemt_user_unique_ips_current{user="hello"} 1220
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 16918.8 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1256701
telemt_connections_bad_total 111358
telemt_connections_current 3958
telemt_connections_me_current 3958
telemt_handshake_timeouts_total 25724
telemt_upstream_connect_attempt_total 2350
telemt_upstream_connect_success_total 2337
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1487
telemt_me_reconnect_success_total 1472
telemt_me_reader_eof_total 1564
telemt_me_idle_close_by_peer_total 1564
telemt_me_route_drop_no_conn_total 519629
telemt_me_route_drop_channel_closed_total 49
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 999367
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4705
telemt_desync_full_logged_total 1459
telemt_desync_suppressed_total 3246
telemt_desync_frames_bucket_total{bucket="1_2"} 1156
telemt_desync_frames_bucket_total{bucket="3_10"} 1783
telemt_desync_frames_bucket_total{bucket="gt_10"} 1766
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 1515
telemt_me_writer_restored_same_endpoint_total 1455
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 998664
telemt_user_connections_current{user="hello"} 3958
telemt_user_octets_from_client{user="hello"} 22377329724 (20.84 GB)
telemt_user_octets_to_client{user="hello"} 454644544132 (423.42 GB)
telemt_user_unique_ips_current{user="hello"} 1135
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 17633.2 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1864530
telemt_connections_bad_total 40620
telemt_connections_current 2791
telemt_connections_me_current 2791
telemt_handshake_timeouts_total 19396
telemt_upstream_connect_attempt_total 2644
telemt_upstream_connect_success_total 2625
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1728
telemt_me_reconnect_success_total 1706
telemt_me_reader_eof_total 1760
telemt_me_idle_close_by_peer_total 1759
telemt_me_route_drop_no_conn_total 3300145
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1672978
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6201
telemt_desync_full_logged_total 1517
telemt_desync_suppressed_total 4684
telemt_desync_frames_bucket_total{bucket="1_2"} 1375
telemt_desync_frames_bucket_total{bucket="3_10"} 2939
telemt_desync_frames_bucket_total{bucket="gt_10"} 1887
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 1713
telemt_me_writer_restored_same_endpoint_total 1695
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1672909
telemt_user_connections_current{user="hello"} 2791
telemt_user_octets_from_client{user="hello"} 15134935540 (14.10 GB)
telemt_user_octets_to_client{user="hello"} 259558825388 (241.73 GB)
telemt_user_unique_ips_current{user="hello"} 889
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12148.3 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901675
telemt_connections_bad_total 155086
telemt_handshake_timeouts_total 8457
telemt_upstream_connect_attempt_total 2108
telemt_upstream_connect_success_total 2042
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 2108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 3494
telemt_me_reconnect_success_total 1400
telemt_me_reader_eof_total 1498
telemt_me_idle_close_by_peer_total 1498
telemt_me_route_drop_no_conn_total 383368
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667593
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2388
telemt_desync_full_logged_total 823
telemt_desync_suppressed_total 1565
telemt_desync_frames_bucket_total{bucket="1_2"} 460
telemt_desync_frames_bucket_total{bucket="3_10"} 819
telemt_desync_frames_bucket_total{bucket="gt_10"} 1109
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1487
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1374
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 667085
telemt_user_connections_current{user="hello"} 3441
telemt_user_octets_from_client{user="hello"} 11658183676 (10.86 GB)
telemt_user_octets_to_client{user="hello"} 294124679960 (273.92 GB)
telemt_user_unique_ips_current{user="hello"} 1114
telemt_user_unique_ips_recent_window{user="hello"} 394
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 17082.3 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295630
telemt_connections_bad_total 10454
telemt_connections_current 772
telemt_connections_me_current 772
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3071
telemt_upstream_connect_attempt_total 6996
telemt_upstream_connect_success_total 6976
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 6996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 331753
telemt_me_reconnect_success_total 2285
telemt_me_reader_eof_total 2300
telemt_me_idle_close_by_peer_total 2300
telemt_me_route_drop_no_conn_total 188015
telemt_me_route_drop_channel_closed_total 90
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262988
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 526
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 14
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2236
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2274
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 266679
telemt_user_connections_current{user="hello"} 772
telemt_user_octets_from_client{user="hello"} 3723801637 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 55978104545 (52.13 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 16152.8 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964830
telemt_connections_bad_total 65232
telemt_connections_current 3420
telemt_connections_me_current 3420
telemt_handshake_timeouts_total 18153
telemt_upstream_connect_attempt_total 2717
telemt_upstream_connect_success_total 2716
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17408
telemt_me_reconnect_success_total 1891
telemt_me_reader_eof_total 1899
telemt_me_idle_close_by_peer_total 1899
telemt_me_route_drop_no_conn_total 475707
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813698
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3376
telemt_desync_full_logged_total 1149
telemt_desync_suppressed_total 2227
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 1192
telemt_desync_frames_bucket_total{bucket="gt_10"} 1404
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1860
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1830
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 812661
telemt_user_connections_current{user="hello"} 3420
telemt_user_octets_from_client{user="hello"} 16247593248 (15.13 GB)
telemt_user_octets_to_client{user="hello"} 438776060196 (408.64 GB)
telemt_user_unique_ips_current{user="hello"} 973
telemt_user_unique_ips_recent_window{user="hello"} 372
```