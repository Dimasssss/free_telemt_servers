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

# Server Metrics 2026-03-18 19:13:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13705.0 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361357
telemt_connections_bad_total 22043
telemt_handshake_timeouts_total 7981
telemt_upstream_connect_attempt_total 2387
telemt_upstream_connect_success_total 2387
telemt_upstream_connect_attempts_per_request{bucket="1"} 2387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 1670
telemt_me_reconnect_success_total 1663
telemt_me_reader_eof_total 1716
telemt_me_idle_close_by_peer_total 1716
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 156613
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311114
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1905
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 1370
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 596
telemt_desync_frames_bucket_total{bucket="gt_10"} 851
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1693
telemt_me_writer_restored_same_endpoint_total 1645
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 310993
telemt_user_connections_current{user="hello"} 1136
telemt_user_octets_from_client{user="hello"} 5731154448 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 104278637392 (97.12 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 18532.4 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1798408
telemt_connections_bad_total 120653
telemt_connections_current 3829
telemt_connections_me_current 3829
telemt_handshake_timeouts_total 31622
telemt_upstream_connect_attempt_total 2990
telemt_upstream_connect_success_total 2976
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2041
telemt_me_reconnect_success_total 2024
telemt_me_reader_eof_total 2027
telemt_me_idle_close_by_peer_total 2026
telemt_me_route_drop_no_conn_total 1696633
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1557161
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5164
telemt_desync_full_logged_total 1659
telemt_desync_suppressed_total 3505
telemt_desync_frames_bucket_total{bucket="1_2"} 906
telemt_desync_frames_bucket_total{bucket="3_10"} 2048
telemt_desync_frames_bucket_total{bucket="gt_10"} 2210
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 1975
telemt_me_writer_restored_same_endpoint_total 2022
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1552347
telemt_user_connections_current{user="hello"} 3829
telemt_user_octets_from_client{user="hello"} 23937667052 (22.29 GB)
telemt_user_octets_to_client{user="hello"} 488989176956 (455.41 GB)
telemt_user_unique_ips_current{user="hello"} 1196
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 18461.0 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1363483
telemt_connections_bad_total 116701
telemt_connections_current 3276
telemt_connections_me_current 3276
telemt_handshake_timeouts_total 28381
telemt_upstream_connect_attempt_total 2614
telemt_upstream_connect_success_total 2600
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1663
telemt_me_reconnect_success_total 1648
telemt_me_reader_eof_total 1747
telemt_me_idle_close_by_peer_total 1747
telemt_me_route_drop_no_conn_total 558195
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1085976
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5155
telemt_desync_full_logged_total 1590
telemt_desync_suppressed_total 3565
telemt_desync_frames_bucket_total{bucket="1_2"} 1279
telemt_desync_frames_bucket_total{bucket="3_10"} 1962
telemt_desync_frames_bucket_total{bucket="gt_10"} 1914
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 1694
telemt_me_writer_restored_same_endpoint_total 1631
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1085283
telemt_user_connections_current{user="hello"} 3276
telemt_user_octets_from_client{user="hello"} 23994545336 (22.35 GB)
telemt_user_octets_to_client{user="hello"} 508325337660 (473.41 GB)
telemt_user_unique_ips_current{user="hello"} 1060
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 19175.6 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2022030
telemt_connections_bad_total 48801
telemt_connections_current 2715
telemt_connections_me_current 2715
telemt_handshake_timeouts_total 20647
telemt_upstream_connect_attempt_total 2918
telemt_upstream_connect_success_total 2889
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1909
telemt_me_reconnect_success_total 1884
telemt_me_reader_eof_total 1948
telemt_me_idle_close_by_peer_total 1947
telemt_me_route_drop_no_conn_total 3602068
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1810598
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6640
telemt_desync_full_logged_total 1641
telemt_desync_suppressed_total 4999
telemt_desync_frames_bucket_total{bucket="1_2"} 1483
telemt_desync_frames_bucket_total{bucket="3_10"} 3134
telemt_desync_frames_bucket_total{bucket="gt_10"} 2023
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 1895
telemt_me_writer_restored_same_endpoint_total 1873
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 1810515
telemt_user_connections_current{user="hello"} 2715
telemt_user_octets_from_client{user="hello"} 16236438112 (15.12 GB)
telemt_user_octets_to_client{user="hello"} 280305110936 (261.05 GB)
telemt_user_unique_ips_current{user="hello"} 870
telemt_user_unique_ips_recent_window{user="hello"} 350
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13690.3 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1010435
telemt_connections_bad_total 176340
telemt_handshake_timeouts_total 9533
telemt_upstream_connect_attempt_total 2422
telemt_upstream_connect_success_total 2343
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 2422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 3709
telemt_me_reconnect_success_total 1613
telemt_me_reader_eof_total 1714
telemt_me_idle_close_by_peer_total 1714
telemt_me_route_drop_no_conn_total 436939
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 745289
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2567
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 1675
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 884
telemt_desync_frames_bucket_total{bucket="gt_10"} 1193
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1703
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1587
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 744705
telemt_user_connections_current{user="hello"} 3326
telemt_user_octets_from_client{user="hello"} 12750975632 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 337099714468 (313.95 GB)
telemt_user_unique_ips_current{user="hello"} 1087
telemt_user_unique_ips_recent_window{user="hello"} 413
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 18623.3 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315459
telemt_connections_bad_total 10491
telemt_connections_current 693
telemt_connections_me_current 693
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3337
telemt_upstream_connect_attempt_total 7263
telemt_upstream_connect_success_total 7240
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 7263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 331931
telemt_me_reconnect_success_total 2462
telemt_me_reader_eof_total 2490
telemt_me_idle_close_by_peer_total 2490
telemt_me_route_drop_no_conn_total 197237
telemt_me_route_drop_channel_closed_total 93
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281177
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 547
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2414
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2451
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 284864
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 4088888125 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 60527348829 (56.37 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 17694.6 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1075626
telemt_connections_bad_total 89865
telemt_connections_current 2942
telemt_connections_me_current 2942
telemt_handshake_timeouts_total 20264
telemt_upstream_connect_attempt_total 2968
telemt_upstream_connect_success_total 2967
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17573
telemt_me_reconnect_success_total 2054
telemt_me_reader_eof_total 2077
telemt_me_idle_close_by_peer_total 2077
telemt_me_route_drop_no_conn_total 504045
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 890612
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3678
telemt_desync_full_logged_total 1251
telemt_desync_suppressed_total 2427
telemt_desync_frames_bucket_total{bucket="1_2"} 857
telemt_desync_frames_bucket_total{bucket="3_10"} 1284
telemt_desync_frames_bucket_total{bucket="gt_10"} 1537
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2028
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1993
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 889555
telemt_user_connections_current{user="hello"} 2942
telemt_user_octets_from_client{user="hello"} 17656637396 (16.44 GB)
telemt_user_octets_to_client{user="hello"} 499348627792 (465.05 GB)
telemt_user_unique_ips_current{user="hello"} 914
telemt_user_unique_ips_recent_window{user="hello"} 370
```