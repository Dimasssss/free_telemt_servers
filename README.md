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

# Server Metrics 2026-03-18 12:54:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 15221.1 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557737
telemt_connections_bad_total 16439
telemt_handshake_timeouts_total 15417
telemt_upstream_connect_attempt_total 65989
telemt_upstream_connect_success_total 65040
telemt_upstream_connect_fail_total 949
telemt_upstream_connect_attempts_per_request{bucket="1"} 65989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 949
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 512663
telemt_me_reconnect_success_total 2295
telemt_me_reader_eof_total 2406
telemt_me_idle_close_by_peer_total 2404
telemt_me_route_drop_no_conn_total 333236
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427659
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1881
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1257
telemt_desync_frames_bucket_total{bucket="1_2"} 525
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 693
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2421
telemt_me_refill_failed_total 16632
telemt_me_writer_restored_same_endpoint_total 2190
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 485892
telemt_user_connections_current{user="hello"} 1809
telemt_user_octets_from_client{user="hello"} 6594583628 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 125049444221 (116.46 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 577
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 15252.1 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1516227
telemt_connections_bad_total 111476
telemt_handshake_timeouts_total 34312
telemt_upstream_connect_attempt_total 2697
telemt_upstream_connect_success_total 2685
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3000
telemt_me_reconnect_success_total 1863
telemt_me_reader_eof_total 1924
telemt_me_idle_close_by_peer_total 1923
telemt_me_route_drop_no_conn_total 1298033
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1299600
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4091
telemt_desync_full_logged_total 1249
telemt_desync_suppressed_total 2842
telemt_desync_frames_bucket_total{bucket="1_2"} 819
telemt_desync_frames_bucket_total{bucket="3_10"} 1652
telemt_desync_frames_bucket_total{bucket="gt_10"} 1620
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1906
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1862
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 1298612
telemt_user_connections_current{user="hello"} 4376
telemt_user_octets_from_client{user="hello"} 32196101672 (29.98 GB)
telemt_user_octets_to_client{user="hello"} 385035921040 (358.59 GB)
telemt_user_unique_ips_current{user="hello"} 1291
telemt_user_unique_ips_recent_window{user="hello"} 646
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 15167.1 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1076961
telemt_connections_bad_total 77827
telemt_handshake_timeouts_total 26081
telemt_upstream_connect_attempt_total 11092
telemt_upstream_connect_success_total 11092
telemt_upstream_connect_attempts_per_request{bucket="1"} 11092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607777
telemt_me_reconnect_success_total 2080
telemt_me_reader_eof_total 2109
telemt_me_idle_close_by_peer_total 2108
telemt_me_route_drop_no_conn_total 454072
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 824041
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2419
telemt_desync_full_logged_total 828
telemt_desync_suppressed_total 1591
telemt_desync_frames_bucket_total{bucket="1_2"} 689
telemt_desync_frames_bucket_total{bucket="3_10"} 887
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2093
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 2045
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 831536
telemt_user_connections_current{user="hello"} 3255
telemt_user_octets_from_client{user="hello"} 10191825703 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 344325149440 (320.68 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 986
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 15197.4 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1778503
telemt_connections_bad_total 25235
telemt_handshake_timeouts_total 167992
telemt_upstream_connect_attempt_total 12437
telemt_upstream_connect_success_total 12248
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 12437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2829837
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1720
telemt_me_idle_close_by_peer_total 1720
telemt_me_route_drop_no_conn_total 2674886
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1441622
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3098
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 2154
telemt_desync_frames_bucket_total{bucket="1_2"} 793
telemt_desync_frames_bucket_total{bucket="3_10"} 1299
telemt_desync_frames_bucket_total{bucket="gt_10"} 1006
telemt_me_writer_removed_unexpected_total 1767
telemt_me_refill_failed_total 100133
telemt_me_writer_restored_same_endpoint_total 1084
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 1460200
telemt_user_connections_current{user="hello"} 3137
telemt_user_octets_from_client{user="hello"} 22328996006 (20.80 GB)
telemt_user_octets_to_client{user="hello"} 221451894897 (206.24 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 913
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 15092.3 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1121366
telemt_connections_bad_total 51108
telemt_handshake_timeouts_total 19500
telemt_upstream_connect_attempt_total 12146
telemt_upstream_connect_success_total 12145
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 2984967
telemt_me_reconnect_success_total 1850
telemt_me_reader_eof_total 1888
telemt_me_idle_close_by_peer_total 1888
telemt_me_route_drop_no_conn_total 700179
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954234
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3150
telemt_desync_full_logged_total 1055
telemt_desync_suppressed_total 2095
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 1234
telemt_desync_frames_bucket_total{bucket="gt_10"} 1460
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1865
telemt_me_refill_failed_total 107189
telemt_me_writer_restored_same_endpoint_total 1735
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 954390
telemt_user_connections_current{user="hello"} 3410
telemt_user_octets_from_client{user="hello"} 15181769761 (14.14 GB)
telemt_user_octets_to_client{user="hello"} 362293975449 (337.41 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1084
telemt_user_unique_ips_recent_window{user="hello"} 544
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 14977.7 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322553
telemt_connections_bad_total 30861
telemt_handshake_timeouts_total 2454
telemt_upstream_connect_attempt_total 2850
telemt_upstream_connect_success_total 2850
telemt_upstream_connect_attempts_per_request{bucket="1"} 2850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 7139
telemt_me_reconnect_success_total 2029
telemt_me_reader_eof_total 2224
telemt_me_idle_close_by_peer_total 2223
telemt_me_route_drop_no_conn_total 173905
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275534
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 694
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2206
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 2021
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 265819
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 4461051592 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 55999532784 (52.15 GB)
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 15048.2 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918811
telemt_connections_bad_total 117031
telemt_handshake_timeouts_total 19562
telemt_upstream_connect_attempt_total 2726
telemt_upstream_connect_success_total 2699
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 1920
telemt_me_reconnect_success_total 1889
telemt_me_reader_eof_total 1939
telemt_me_idle_close_by_peer_total 1939
telemt_me_route_drop_no_conn_total 420036
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 712416
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2567
telemt_desync_full_logged_total 876
telemt_desync_suppressed_total 1691
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 891
telemt_desync_frames_bucket_total{bucket="gt_10"} 1235
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1902
telemt_me_writer_restored_same_endpoint_total 1879
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 711890
telemt_user_connections_current{user="hello"} 2851
telemt_user_octets_from_client{user="hello"} 15120470432 (14.08 GB)
telemt_user_octets_to_client{user="hello"} 347722514220 (323.84 GB)
telemt_user_unique_ips_current{user="hello"} 876
telemt_user_unique_ips_recent_window{user="hello"} 408
```