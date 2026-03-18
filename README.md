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

# Server Metrics 2026-03-18 19:18:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14011.7 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367218
telemt_connections_bad_total 22300
telemt_handshake_timeouts_total 8065
telemt_upstream_connect_attempt_total 2471
telemt_upstream_connect_success_total 2471
telemt_upstream_connect_attempts_per_request{bucket="1"} 2471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 1754
telemt_me_reconnect_success_total 1747
telemt_me_reader_eof_total 1800
telemt_me_idle_close_by_peer_total 1800
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 158902
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316442
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1934
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 868
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1777
telemt_me_writer_restored_same_endpoint_total 1729
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 316323
telemt_user_connections_current{user="hello"} 1258
telemt_user_octets_from_client{user="hello"} 5806568576 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 106868627440 (99.53 GB)
telemt_user_unique_ips_current{user="hello"} 434
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 18839.8 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1820493
telemt_connections_bad_total 121286
telemt_connections_current 3846
telemt_connections_me_current 3846
telemt_handshake_timeouts_total 31825
telemt_upstream_connect_attempt_total 3006
telemt_upstream_connect_success_total 2992
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2057
telemt_me_reconnect_success_total 2040
telemt_me_reader_eof_total 2043
telemt_me_idle_close_by_peer_total 2042
telemt_me_route_drop_no_conn_total 1708687
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1577336
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5257
telemt_desync_full_logged_total 1686
telemt_desync_suppressed_total 3571
telemt_desync_frames_bucket_total{bucket="1_2"} 924
telemt_desync_frames_bucket_total{bucket="3_10"} 2088
telemt_desync_frames_bucket_total{bucket="gt_10"} 2245
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 1991
telemt_me_writer_restored_same_endpoint_total 2038
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1572532
telemt_user_connections_current{user="hello"} 3846
telemt_user_octets_from_client{user="hello"} 24287268192 (22.62 GB)
telemt_user_octets_to_client{user="hello"} 498552612144 (464.31 GB)
telemt_user_unique_ips_current{user="hello"} 1200
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 18768.6 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1381986
telemt_connections_bad_total 117659
telemt_connections_current 3338
telemt_connections_me_current 3338
telemt_handshake_timeouts_total 28864
telemt_upstream_connect_attempt_total 2651
telemt_upstream_connect_success_total 2637
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1699
telemt_me_reconnect_success_total 1683
telemt_me_reader_eof_total 1782
telemt_me_idle_close_by_peer_total 1782
telemt_me_route_drop_no_conn_total 565314
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1102004
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5205
telemt_desync_full_logged_total 1608
telemt_desync_suppressed_total 3597
telemt_desync_frames_bucket_total{bucket="1_2"} 1295
telemt_desync_frames_bucket_total{bucket="3_10"} 1979
telemt_desync_frames_bucket_total{bucket="gt_10"} 1931
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 1729
telemt_me_writer_restored_same_endpoint_total 1666
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1101311
telemt_user_connections_current{user="hello"} 3338
telemt_user_octets_from_client{user="hello"} 24308865592 (22.64 GB)
telemt_user_octets_to_client{user="hello"} 520080136788 (484.36 GB)
telemt_user_unique_ips_current{user="hello"} 1087
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 19482.7 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2038856
telemt_connections_bad_total 50558
telemt_connections_current 2639
telemt_connections_me_current 2639
telemt_handshake_timeouts_total 20867
telemt_upstream_connect_attempt_total 2955
telemt_upstream_connect_success_total 2926
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1946
telemt_me_reconnect_success_total 1921
telemt_me_reader_eof_total 1985
telemt_me_idle_close_by_peer_total 1984
telemt_me_route_drop_no_conn_total 3612108
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1824463
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6706
telemt_desync_full_logged_total 1667
telemt_desync_suppressed_total 5039
telemt_desync_frames_bucket_total{bucket="1_2"} 1492
telemt_desync_frames_bucket_total{bucket="3_10"} 3156
telemt_desync_frames_bucket_total{bucket="gt_10"} 2058
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 1932
telemt_me_writer_restored_same_endpoint_total 1910
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 1824380
telemt_user_connections_current{user="hello"} 2639
telemt_user_octets_from_client{user="hello"} 16387690648 (15.26 GB)
telemt_user_octets_to_client{user="hello"} 285795009876 (266.17 GB)
telemt_user_unique_ips_current{user="hello"} 865
telemt_user_unique_ips_recent_window{user="hello"} 314
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13997.6 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1032824
telemt_connections_bad_total 181870
telemt_handshake_timeouts_total 10070
telemt_upstream_connect_attempt_total 2500
telemt_upstream_connect_success_total 2421
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 2500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 3787
telemt_me_reconnect_success_total 1692
telemt_me_reader_eof_total 1796
telemt_me_idle_close_by_peer_total 1796
telemt_me_route_drop_no_conn_total 446062
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759853
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2634
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 1703
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 904
telemt_desync_frames_bucket_total{bucket="gt_10"} 1224
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1785
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1666
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 759260
telemt_user_connections_current{user="hello"} 3227
telemt_user_octets_from_client{user="hello"} 13073214632 (12.18 GB)
telemt_user_octets_to_client{user="hello"} 345630016408 (321.89 GB)
telemt_user_unique_ips_current{user="hello"} 1074
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 18930.9 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318800
telemt_connections_bad_total 10492
telemt_connections_current 794
telemt_connections_me_current 794
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3360
telemt_upstream_connect_attempt_total 7286
telemt_upstream_connect_success_total 7262
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 7285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 331953
telemt_me_reconnect_success_total 2482
telemt_me_reader_eof_total 2513
telemt_me_idle_close_by_peer_total 2513
telemt_me_route_drop_no_conn_total 198894
telemt_me_route_drop_channel_closed_total 93
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284325
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 562
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 222
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2437
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2471
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 288012
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 4233638217 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 61618807881 (57.39 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 18001.8 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1092101
telemt_connections_bad_total 91943
telemt_connections_current 2962
telemt_connections_me_current 2962
telemt_handshake_timeouts_total 20674
telemt_upstream_connect_attempt_total 2992
telemt_upstream_connect_success_total 2990
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17597
telemt_me_reconnect_success_total 2077
telemt_me_reader_eof_total 2103
telemt_me_idle_close_by_peer_total 2103
telemt_me_route_drop_no_conn_total 511517
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904186
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3715
telemt_desync_full_logged_total 1268
telemt_desync_suppressed_total 2447
telemt_desync_frames_bucket_total{bucket="1_2"} 860
telemt_desync_frames_bucket_total{bucket="3_10"} 1300
telemt_desync_frames_bucket_total{bucket="gt_10"} 1555
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2054
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2016
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 902977
telemt_user_connections_current{user="hello"} 2962
telemt_user_octets_from_client{user="hello"} 17843016688 (16.62 GB)
telemt_user_octets_to_client{user="hello"} 510122059536 (475.09 GB)
telemt_user_unique_ips_current{user="hello"} 922
telemt_user_unique_ips_recent_window{user="hello"} 337
```