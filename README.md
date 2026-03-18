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

# Server Metrics 2026-03-18 19:39:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 15255.8 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391723
telemt_connections_bad_total 23330
telemt_handshake_timeouts_total 8378
telemt_upstream_connect_attempt_total 2704
telemt_upstream_connect_success_total 2704
telemt_upstream_connect_attempts_per_request{bucket="1"} 2704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1944
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 2011
telemt_me_idle_close_by_peer_total 2011
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 166381
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338594
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2023
telemt_desync_full_logged_total 569
telemt_desync_suppressed_total 1454
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 911
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1970
telemt_me_writer_restored_same_endpoint_total 1918
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 338471
telemt_user_connections_current{user="hello"} 1220
telemt_user_octets_from_client{user="hello"} 6839969028 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 119551314728 (111.34 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 20084.1 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1913368
telemt_connections_bad_total 132964
telemt_connections_current 3469
telemt_connections_me_current 3469
telemt_handshake_timeouts_total 33018
telemt_upstream_connect_attempt_total 3218
telemt_upstream_connect_success_total 3202
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2181
telemt_me_reconnect_success_total 2164
telemt_me_reader_eof_total 2177
telemt_me_idle_close_by_peer_total 2176
telemt_me_route_drop_no_conn_total 1746832
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1653121
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5678
telemt_desync_full_logged_total 1813
telemt_desync_suppressed_total 3865
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 2270
telemt_desync_frames_bucket_total{bucket="gt_10"} 2422
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2117
telemt_me_writer_restored_same_endpoint_total 2162
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1648324
telemt_user_connections_current{user="hello"} 3469
telemt_user_octets_from_client{user="hello"} 25410798680 (23.67 GB)
telemt_user_octets_to_client{user="hello"} 536899190396 (500.03 GB)
telemt_user_unique_ips_current{user="hello"} 1149
telemt_user_unique_ips_recent_window{user="hello"} 439
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 20012.6 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1450574
telemt_connections_bad_total 122515
telemt_connections_current 2977
telemt_connections_me_current 2977
telemt_handshake_timeouts_total 30935
telemt_upstream_connect_attempt_total 2897
telemt_upstream_connect_success_total 2881
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1856
telemt_me_reconnect_success_total 1839
telemt_me_reader_eof_total 1954
telemt_me_idle_close_by_peer_total 1954
telemt_me_route_drop_no_conn_total 591665
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1159515
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5420
telemt_desync_full_logged_total 1681
telemt_desync_suppressed_total 3739
telemt_desync_frames_bucket_total{bucket="1_2"} 1347
telemt_desync_frames_bucket_total{bucket="3_10"} 2054
telemt_desync_frames_bucket_total{bucket="gt_10"} 2019
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 1885
telemt_me_writer_restored_same_endpoint_total 1822
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1158796
telemt_user_connections_current{user="hello"} 2977
telemt_user_octets_from_client{user="hello"} 25101546320 (23.38 GB)
telemt_user_octets_to_client{user="hello"} 560370626264 (521.89 GB)
telemt_user_unique_ips_current{user="hello"} 989
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 20726.8 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2100936
telemt_connections_bad_total 53748
telemt_connections_current 2443
telemt_connections_me_current 2443
telemt_handshake_timeouts_total 21386
telemt_upstream_connect_attempt_total 3130
telemt_upstream_connect_success_total 3100
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2074
telemt_me_reconnect_success_total 2049
telemt_me_reader_eof_total 2123
telemt_me_idle_close_by_peer_total 2122
telemt_me_route_drop_no_conn_total 3651054
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1878920
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6966
telemt_desync_full_logged_total 1768
telemt_desync_suppressed_total 5198
telemt_desync_frames_bucket_total{bucket="1_2"} 1534
telemt_desync_frames_bucket_total{bucket="3_10"} 3274
telemt_desync_frames_bucket_total{bucket="gt_10"} 2158
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2061
telemt_me_writer_restored_same_endpoint_total 2038
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 1878828
telemt_user_connections_current{user="hello"} 2443
telemt_user_octets_from_client{user="hello"} 17139688608 (15.96 GB)
telemt_user_octets_to_client{user="hello"} 306624906312 (285.57 GB)
telemt_user_unique_ips_current{user="hello"} 839
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15241.9 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1114518
telemt_connections_bad_total 200023
telemt_handshake_timeouts_total 10805
telemt_upstream_connect_attempt_total 2687
telemt_upstream_connect_success_total 2605
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 2687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 3928
telemt_me_reconnect_success_total 1832
telemt_me_reader_eof_total 1951
telemt_me_idle_close_by_peer_total 1951
telemt_me_route_drop_no_conn_total 482523
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 817745
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2903
telemt_desync_full_logged_total 1031
telemt_desync_suppressed_total 1872
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 988
telemt_desync_frames_bucket_total{bucket="gt_10"} 1370
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1929
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1806
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 817135
telemt_user_connections_current{user="hello"} 3212
telemt_user_octets_from_client{user="hello"} 14146353664 (13.17 GB)
telemt_user_octets_to_client{user="hello"} 379932560532 (353.84 GB)
telemt_user_unique_ips_current{user="hello"} 1065
telemt_user_unique_ips_recent_window{user="hello"} 402
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 20175.5 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334159
telemt_connections_bad_total 10590
telemt_connections_current 735
telemt_connections_me_current 735
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3591
telemt_upstream_connect_attempt_total 7551
telemt_upstream_connect_success_total 7522
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 332126
telemt_me_reconnect_success_total 2656
telemt_me_reader_eof_total 2700
telemt_me_idle_close_by_peer_total 2700
telemt_me_route_drop_no_conn_total 204866
telemt_me_route_drop_channel_closed_total 98
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296912
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 588
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 371
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 18
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2611
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2645
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 300596
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 5093250017 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 65793704717 (61.28 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 19246.2 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1151050
telemt_connections_bad_total 96774
telemt_connections_current 3012
telemt_connections_me_current 3012
telemt_handshake_timeouts_total 22197
telemt_upstream_connect_attempt_total 3233
telemt_upstream_connect_success_total 3232
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17752
telemt_me_reconnect_success_total 2232
telemt_me_reader_eof_total 2269
telemt_me_idle_close_by_peer_total 2269
telemt_me_route_drop_no_conn_total 530021
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954768
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4037
telemt_desync_full_logged_total 1364
telemt_desync_suppressed_total 2673
telemt_desync_frames_bucket_total{bucket="1_2"} 906
telemt_desync_frames_bucket_total{bucket="3_10"} 1423
telemt_desync_frames_bucket_total{bucket="gt_10"} 1708
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2210
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2171
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 953553
telemt_user_connections_current{user="hello"} 3012
telemt_user_octets_from_client{user="hello"} 19093371560 (17.78 GB)
telemt_user_octets_to_client{user="hello"} 546035155172 (508.53 GB)
telemt_user_unique_ips_current{user="hello"} 879
telemt_user_unique_ips_recent_window{user="hello"} 329
```