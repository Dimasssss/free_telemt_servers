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

# Server Metrics 2026-03-18 18:58:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12776.5 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341980
telemt_connections_bad_total 21104
telemt_handshake_timeouts_total 7616
telemt_upstream_connect_attempt_total 2155
telemt_upstream_connect_success_total 2155
telemt_upstream_connect_attempts_per_request{bucket="1"} 2155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1481
telemt_me_reconnect_success_total 1474
telemt_me_reader_eof_total 1528
telemt_me_idle_close_by_peer_total 1528
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 149840
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293787
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1740
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 1240
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 778
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1502
telemt_me_writer_restored_same_endpoint_total 1458
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 293667
telemt_user_connections_current{user="hello"} 1186
telemt_user_octets_from_client{user="hello"} 5507685196 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 97968802864 (91.24 GB)
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 17604.8 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1709096
telemt_connections_bad_total 112171
telemt_connections_current 4114
telemt_connections_me_current 4114
telemt_handshake_timeouts_total 30991
telemt_upstream_connect_attempt_total 2872
telemt_upstream_connect_success_total 2858
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1966
telemt_me_reconnect_success_total 1950
telemt_me_reader_eof_total 1945
telemt_me_idle_close_by_peer_total 1944
telemt_me_route_drop_no_conn_total 1622618
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1481229
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4844
telemt_desync_full_logged_total 1549
telemt_desync_suppressed_total 3295
telemt_desync_frames_bucket_total{bucket="1_2"} 835
telemt_desync_frames_bucket_total{bucket="3_10"} 1922
telemt_desync_frames_bucket_total{bucket="gt_10"} 2087
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1897
telemt_me_writer_restored_same_endpoint_total 1948
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1476398
telemt_user_connections_current{user="hello"} 4114
telemt_user_octets_from_client{user="hello"} 19450728684 (18.11 GB)
telemt_user_octets_to_client{user="hello"} 464097399996 (432.22 GB)
telemt_user_unique_ips_current{user="hello"} 1233
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 17532.8 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1303393
telemt_connections_bad_total 113755
telemt_connections_current 3623
telemt_connections_me_current 3623
telemt_handshake_timeouts_total 26723
telemt_upstream_connect_attempt_total 2454
telemt_upstream_connect_success_total 2441
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1548
telemt_me_reconnect_success_total 1533
telemt_me_reader_eof_total 1630
telemt_me_idle_close_by_peer_total 1630
telemt_me_route_drop_no_conn_total 534977
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1035153
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4943
telemt_desync_full_logged_total 1515
telemt_desync_suppressed_total 3428
telemt_desync_frames_bucket_total{bucket="1_2"} 1228
telemt_desync_frames_bucket_total{bucket="3_10"} 1872
telemt_desync_frames_bucket_total{bucket="gt_10"} 1843
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 1577
telemt_me_writer_restored_same_endpoint_total 1516
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1034447
telemt_user_connections_current{user="hello"} 3623
telemt_user_octets_from_client{user="hello"} 22971292924 (21.39 GB)
telemt_user_octets_to_client{user="hello"} 474256670244 (441.69 GB)
telemt_user_unique_ips_current{user="hello"} 1100
telemt_user_unique_ips_recent_window{user="hello"} 404
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 18247.4 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1931262
telemt_connections_bad_total 44089
telemt_connections_current 2870
telemt_connections_me_current 2870
telemt_handshake_timeouts_total 19760
telemt_upstream_connect_attempt_total 2757
telemt_upstream_connect_success_total 2736
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1796
telemt_me_reconnect_success_total 1774
telemt_me_reader_eof_total 1834
telemt_me_idle_close_by_peer_total 1833
telemt_me_route_drop_no_conn_total 3400909
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1732373
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6354
telemt_desync_full_logged_total 1565
telemt_desync_suppressed_total 4789
telemt_desync_frames_bucket_total{bucket="1_2"} 1417
telemt_desync_frames_bucket_total{bucket="3_10"} 3012
telemt_desync_frames_bucket_total{bucket="gt_10"} 1925
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 1781
telemt_me_writer_restored_same_endpoint_total 1763
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1732300
telemt_user_connections_current{user="hello"} 2870
telemt_user_octets_from_client{user="hello"} 15587165636 (14.52 GB)
telemt_user_octets_to_client{user="hello"} 268342733020 (249.91 GB)
telemt_user_unique_ips_current{user="hello"} 912
telemt_user_unique_ips_recent_window{user="hello"} 410
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12762.4 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946553
telemt_connections_bad_total 166810
telemt_handshake_timeouts_total 8730
telemt_upstream_connect_attempt_total 2207
telemt_upstream_connect_success_total 2134
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 2207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 3543
telemt_me_reconnect_success_total 1448
telemt_me_reader_eof_total 1548
telemt_me_idle_close_by_peer_total 1548
telemt_me_route_drop_no_conn_total 402240
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697627
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2465
telemt_desync_full_logged_total 852
telemt_desync_suppressed_total 1613
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 847
telemt_desync_frames_bucket_total{bucket="gt_10"} 1153
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1537
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1422
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 697058
telemt_user_connections_current{user="hello"} 3318
telemt_user_octets_from_client{user="hello"} 12147053124 (11.31 GB)
telemt_user_octets_to_client{user="hello"} 311103675088 (289.74 GB)
telemt_user_unique_ips_current{user="hello"} 1098
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 17697.6 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303319
telemt_connections_bad_total 10458
telemt_connections_current 751
telemt_connections_me_current 751
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3187
telemt_upstream_connect_attempt_total 7122
telemt_upstream_connect_success_total 7100
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 7122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3357
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 331834
telemt_me_reconnect_success_total 2365
telemt_me_reader_eof_total 2387
telemt_me_idle_close_by_peer_total 2387
telemt_me_route_drop_no_conn_total 190933
telemt_me_route_drop_channel_closed_total 91
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270072
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 535
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 15
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2317
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2354
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 273763
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 3788047889 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 57528635917 (53.58 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 16766.7 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1006973
telemt_connections_bad_total 70111
telemt_connections_current 3357
telemt_connections_me_current 3357
telemt_handshake_timeouts_total 19108
telemt_upstream_connect_attempt_total 2834
telemt_upstream_connect_success_total 2833
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17482
telemt_me_reconnect_success_total 1964
telemt_me_reader_eof_total 1981
telemt_me_idle_close_by_peer_total 1981
telemt_me_route_drop_no_conn_total 486422
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844961
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3483
telemt_desync_full_logged_total 1186
telemt_desync_suppressed_total 2297
telemt_desync_frames_bucket_total{bucket="1_2"} 815
telemt_desync_frames_bucket_total{bucket="3_10"} 1220
telemt_desync_frames_bucket_total{bucket="gt_10"} 1448
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1936
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1903
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 843921
telemt_user_connections_current{user="hello"} 3358
telemt_user_octets_from_client{user="hello"} 16769981656 (15.62 GB)
telemt_user_octets_to_client{user="hello"} 462835335484 (431.05 GB)
telemt_user_unique_ips_current{user="hello"} 981
telemt_user_unique_ips_recent_window{user="hello"} 361
```