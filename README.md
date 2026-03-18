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

# Server Metrics 2026-03-18 17:56:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9087.8 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257670
telemt_connections_bad_total 16616
telemt_handshake_timeouts_total 6501
telemt_upstream_connect_attempt_total 1458
telemt_upstream_connect_success_total 1457
telemt_upstream_connect_attempts_per_request{bucket="1"} 1457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 965
telemt_me_reconnect_success_total 961
telemt_me_reader_eof_total 989
telemt_me_idle_close_by_peer_total 989
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 118360
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218841
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1184
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 821
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 379
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 982
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 218743
telemt_user_connections_current{user="hello"} 1316
telemt_user_octets_from_client{user="hello"} 3077086952 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 74061547240 (68.98 GB)
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 13915.9 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1404057
telemt_connections_bad_total 85860
telemt_connections_current 3451
telemt_connections_me_current 3451
telemt_handshake_timeouts_total 27144
telemt_upstream_connect_attempt_total 2410
telemt_upstream_connect_success_total 2397
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1677
telemt_me_reconnect_success_total 1663
telemt_me_reader_eof_total 1635
telemt_me_idle_close_by_peer_total 1634
telemt_me_route_drop_no_conn_total 1466219
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1221091
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3647
telemt_desync_full_logged_total 1157
telemt_desync_suppressed_total 2490
telemt_desync_frames_bucket_total{bucket="1_2"} 657
telemt_desync_frames_bucket_total{bucket="3_10"} 1449
telemt_desync_frames_bucket_total{bucket="gt_10"} 1541
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1602
telemt_me_writer_restored_same_endpoint_total 1661
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1216398
telemt_user_connections_current{user="hello"} 3451
telemt_user_octets_from_client{user="hello"} 15895941288 (14.80 GB)
telemt_user_octets_to_client{user="hello"} 356212953468 (331.75 GB)
telemt_user_unique_ips_current{user="hello"} 1133
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 13845.2 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982324
telemt_connections_bad_total 78917
telemt_connections_current 3210
telemt_connections_me_current 3210
telemt_handshake_timeouts_total 21725
telemt_upstream_connect_attempt_total 1964
telemt_upstream_connect_success_total 1953
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1232
telemt_me_reconnect_success_total 1219
telemt_me_reader_eof_total 1292
telemt_me_idle_close_by_peer_total 1292
telemt_me_route_drop_no_conn_total 440358
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 811455
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3447
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 2389
telemt_desync_frames_bucket_total{bucket="1_2"} 842
telemt_desync_frames_bucket_total{bucket="3_10"} 1298
telemt_desync_frames_bucket_total{bucket="gt_10"} 1307
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1256
telemt_me_writer_restored_same_endpoint_total 1202
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 811093
telemt_user_connections_current{user="hello"} 3210
telemt_user_octets_from_client{user="hello"} 19479979720 (18.14 GB)
telemt_user_octets_to_client{user="hello"} 350236739380 (326.18 GB)
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 14558.5 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1456042
telemt_connections_bad_total 34456
telemt_connections_current 2857
telemt_connections_me_current 2857
telemt_handshake_timeouts_total 16518
telemt_upstream_connect_attempt_total 2255
telemt_upstream_connect_success_total 2239
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1471
telemt_me_reconnect_success_total 1451
telemt_me_reader_eof_total 1485
telemt_me_idle_close_by_peer_total 1484
telemt_me_route_drop_no_conn_total 2435755
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1300635
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4941
telemt_desync_full_logged_total 1234
telemt_desync_suppressed_total 3707
telemt_desync_frames_bucket_total{bucket="1_2"} 1132
telemt_desync_frames_bucket_total{bucket="3_10"} 2299
telemt_desync_frames_bucket_total{bucket="gt_10"} 1510
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1451
telemt_me_writer_restored_same_endpoint_total 1440
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1300557
telemt_user_connections_current{user="hello"} 2857
telemt_user_octets_from_client{user="hello"} 12505635232 (11.65 GB)
telemt_user_octets_to_client{user="hello"} 217640615008 (202.69 GB)
telemt_user_unique_ips_current{user="hello"} 894
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9073.5 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678903
telemt_connections_bad_total 126295
telemt_handshake_timeouts_total 6644
telemt_upstream_connect_attempt_total 1635
telemt_upstream_connect_success_total 1581
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 1635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 3182
telemt_me_reconnect_success_total 1092
telemt_me_reader_eof_total 1161
telemt_me_idle_close_by_peer_total 1161
telemt_me_route_drop_no_conn_total 263714
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495040
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1815
telemt_desync_full_logged_total 620
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 869
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1171
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1066
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 494542
telemt_user_connections_current{user="hello"} 2973
telemt_user_octets_from_client{user="hello"} 7930548508 (7.39 GB)
telemt_user_octets_to_client{user="hello"} 211788060120 (197.24 GB)
telemt_user_unique_ips_current{user="hello"} 1025
telemt_user_unique_ips_recent_window{user="hello"} 393
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 14008.3 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254802
telemt_connections_bad_total 9948
telemt_connections_current 857
telemt_connections_me_current 857
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2750
telemt_upstream_connect_attempt_total 6514
telemt_upstream_connect_success_total 6499
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2982
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 331405
telemt_me_reconnect_success_total 1939
telemt_me_reader_eof_total 1927
telemt_me_idle_close_by_peer_total 1927
telemt_me_route_drop_no_conn_total 163715
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225668
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 437
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 276
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 11
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 1882
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1928
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 229384
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 3400378609 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 46868409709 (43.65 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 13078.1 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786293
telemt_connections_bad_total 54729
telemt_connections_current 2740
telemt_connections_me_current 2740
telemt_handshake_timeouts_total 14443
telemt_upstream_connect_attempt_total 2281
telemt_upstream_connect_success_total 2280
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17102
telemt_me_reconnect_success_total 1587
telemt_me_reader_eof_total 1577
telemt_me_idle_close_by_peer_total 1577
telemt_me_route_drop_no_conn_total 419970
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660748
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2600
telemt_desync_full_logged_total 897
telemt_desync_suppressed_total 1703
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 919
telemt_desync_frames_bucket_total{bucket="gt_10"} 1038
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1552
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1526
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 659772
telemt_user_connections_current{user="hello"} 2740
telemt_user_octets_from_client{user="hello"} 12434947448 (11.58 GB)
telemt_user_octets_to_client{user="hello"} 330131302256 (307.46 GB)
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 333
```