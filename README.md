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

# Server Metrics 2026-03-18 19:29:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14642.3 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379789
telemt_connections_bad_total 22817
telemt_handshake_timeouts_total 8201
telemt_upstream_connect_attempt_total 2650
telemt_upstream_connect_success_total 2650
telemt_upstream_connect_attempts_per_request{bucket="1"} 2650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1890
telemt_me_reconnect_success_total 1882
telemt_me_reader_eof_total 1955
telemt_me_idle_close_by_peer_total 1955
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 163030
telemt_me_route_drop_channel_closed_total 72
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327939
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1980
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 1425
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 619
telemt_desync_frames_bucket_total{bucket="gt_10"} 890
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1914
telemt_me_writer_restored_same_endpoint_total 1864
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 327819
telemt_user_connections_current{user="hello"} 1201
telemt_user_octets_from_client{user="hello"} 6433006836 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 112109044372 (104.41 GB)
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 19470.5 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1867931
telemt_connections_bad_total 126884
telemt_connections_current 3654
telemt_connections_me_current 3654
telemt_handshake_timeouts_total 32350
telemt_upstream_connect_attempt_total 3113
telemt_upstream_connect_success_total 3097
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2119
telemt_me_reconnect_success_total 2102
telemt_me_reader_eof_total 2109
telemt_me_idle_close_by_peer_total 2108
telemt_me_route_drop_no_conn_total 1728022
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1616147
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5486
telemt_desync_full_logged_total 1756
telemt_desync_suppressed_total 3730
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 2186
telemt_desync_frames_bucket_total{bucket="gt_10"} 2328
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2053
telemt_me_writer_restored_same_endpoint_total 2100
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1611355
telemt_user_connections_current{user="hello"} 3654
telemt_user_octets_from_client{user="hello"} 24891426496 (23.18 GB)
telemt_user_octets_to_client{user="hello"} 517916984228 (482.35 GB)
telemt_user_unique_ips_current{user="hello"} 1164
telemt_user_unique_ips_recent_window{user="hello"} 439
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 19398.8 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1417560
telemt_connections_bad_total 120275
telemt_connections_current 3155
telemt_connections_me_current 3155
telemt_handshake_timeouts_total 29976
telemt_upstream_connect_attempt_total 2785
telemt_upstream_connect_success_total 2769
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1788
telemt_me_reconnect_success_total 1771
telemt_me_reader_eof_total 1880
telemt_me_idle_close_by_peer_total 1880
telemt_me_route_drop_no_conn_total 578212
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1131484
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5312
telemt_desync_full_logged_total 1645
telemt_desync_suppressed_total 3667
telemt_desync_frames_bucket_total{bucket="1_2"} 1314
telemt_desync_frames_bucket_total{bucket="3_10"} 2016
telemt_desync_frames_bucket_total{bucket="gt_10"} 1982
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 1817
telemt_me_writer_restored_same_endpoint_total 1754
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1130789
telemt_user_connections_current{user="hello"} 3155
telemt_user_octets_from_client{user="hello"} 24686482028 (22.99 GB)
telemt_user_octets_to_client{user="hello"} 539424708516 (502.38 GB)
telemt_user_unique_ips_current{user="hello"} 1030
telemt_user_unique_ips_recent_window{user="hello"} 343
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 20113.6 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2071207
telemt_connections_bad_total 51170
telemt_connections_current 2472
telemt_connections_me_current 2472
telemt_handshake_timeouts_total 21171
telemt_upstream_connect_attempt_total 3074
telemt_upstream_connect_success_total 3044
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1447
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2021
telemt_me_reconnect_success_total 1996
telemt_me_reader_eof_total 2070
telemt_me_idle_close_by_peer_total 2069
telemt_me_route_drop_no_conn_total 3639449
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1853396
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6859
telemt_desync_full_logged_total 1726
telemt_desync_suppressed_total 5133
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 3218
telemt_desync_frames_bucket_total{bucket="gt_10"} 2122
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2008
telemt_me_writer_restored_same_endpoint_total 1985
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 1853309
telemt_user_connections_current{user="hello"} 2472
telemt_user_octets_from_client{user="hello"} 16706119572 (15.56 GB)
telemt_user_octets_to_client{user="hello"} 296158118756 (275.82 GB)
telemt_user_unique_ips_current{user="hello"} 826
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14628.5 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1071295
telemt_connections_bad_total 187434
telemt_handshake_timeouts_total 10337
telemt_upstream_connect_attempt_total 2645
telemt_upstream_connect_success_total 2563
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 2645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 3886
telemt_me_reconnect_success_total 1790
telemt_me_reader_eof_total 1907
telemt_me_idle_close_by_peer_total 1907
telemt_me_route_drop_no_conn_total 464603
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790124
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2776
telemt_desync_full_logged_total 980
telemt_desync_suppressed_total 1796
telemt_desync_frames_bucket_total{bucket="1_2"} 524
telemt_desync_frames_bucket_total{bucket="3_10"} 943
telemt_desync_frames_bucket_total{bucket="gt_10"} 1309
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1885
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1764
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 789517
telemt_user_connections_current{user="hello"} 3224
telemt_user_octets_from_client{user="hello"} 13585394236 (12.65 GB)
telemt_user_octets_to_client{user="hello"} 363189387484 (338.25 GB)
telemt_user_unique_ips_current{user="hello"} 1072
telemt_user_unique_ips_recent_window{user="hello"} 419
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 19563.0 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326597
telemt_connections_bad_total 10508
telemt_connections_current 745
telemt_connections_me_current 745
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3463
telemt_upstream_connect_attempt_total 7423
telemt_upstream_connect_success_total 7396
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 332044
telemt_me_reconnect_success_total 2574
telemt_me_reader_eof_total 2610
telemt_me_idle_close_by_peer_total 2610
telemt_me_route_drop_no_conn_total 202386
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291035
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 581
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 368
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2529
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2563
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 294723
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 4547222141 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 63610200933 (59.24 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 18632.8 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1124036
telemt_connections_bad_total 95638
telemt_connections_current 2850
telemt_connections_me_current 2850
telemt_handshake_timeouts_total 21458
telemt_upstream_connect_attempt_total 3114
telemt_upstream_connect_success_total 3113
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17676
telemt_me_reconnect_success_total 2156
telemt_me_reader_eof_total 2187
telemt_me_idle_close_by_peer_total 2187
telemt_me_route_drop_no_conn_total 521797
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 930425
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3873
telemt_desync_full_logged_total 1315
telemt_desync_suppressed_total 2558
telemt_desync_frames_bucket_total{bucket="1_2"} 884
telemt_desync_frames_bucket_total{bucket="3_10"} 1354
telemt_desync_frames_bucket_total{bucket="gt_10"} 1635
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2134
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2095
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 929212
telemt_user_connections_current{user="hello"} 2850
telemt_user_octets_from_client{user="hello"} 18369693336 (17.11 GB)
telemt_user_octets_to_client{user="hello"} 528244273724 (491.97 GB)
telemt_user_unique_ips_current{user="hello"} 872
telemt_user_unique_ips_recent_window{user="hello"} 311
```