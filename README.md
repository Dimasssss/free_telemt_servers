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

# Server Metrics 2026-03-18 19:54:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16175.1 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409816
telemt_connections_bad_total 24101
telemt_handshake_timeouts_total 9045
telemt_upstream_connect_attempt_total 2896
telemt_upstream_connect_success_total 2893
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 2089
telemt_me_reconnect_success_total 2076
telemt_me_reader_eof_total 2155
telemt_me_idle_close_by_peer_total 2155
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 172463
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354388
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2122
telemt_desync_full_logged_total 597
telemt_desync_suppressed_total 1525
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 670
telemt_desync_frames_bucket_total{bucket="gt_10"} 942
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2115
telemt_me_writer_restored_same_endpoint_total 2058
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 354267
telemt_user_connections_current{user="hello"} 1184
telemt_user_octets_from_client{user="hello"} 7118212104 (6.63 GB)
telemt_user_octets_to_client{user="hello"} 126029300180 (117.37 GB)
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 21003.5 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1971659
telemt_connections_bad_total 137882
telemt_connections_current 3323
telemt_connections_me_current 3323
telemt_handshake_timeouts_total 33974
telemt_upstream_connect_attempt_total 3358
telemt_upstream_connect_success_total 3340
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2276
telemt_me_reconnect_success_total 2259
telemt_me_reader_eof_total 2280
telemt_me_idle_close_by_peer_total 2279
telemt_me_route_drop_no_conn_total 1769342
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1703700
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5945
telemt_desync_full_logged_total 1909
telemt_desync_suppressed_total 4036
telemt_desync_frames_bucket_total{bucket="1_2"} 1030
telemt_desync_frames_bucket_total{bucket="3_10"} 2365
telemt_desync_frames_bucket_total{bucket="gt_10"} 2550
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2214
telemt_me_writer_restored_same_endpoint_total 2257
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1698950
telemt_user_connections_current{user="hello"} 3323
telemt_user_octets_from_client{user="hello"} 26156019608 (24.36 GB)
telemt_user_octets_to_client{user="hello"} 562916761316 (524.26 GB)
telemt_user_unique_ips_current{user="hello"} 1084
telemt_user_unique_ips_recent_window{user="hello"} 422
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 20932.4 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1498672
telemt_connections_bad_total 124598
telemt_connections_current 3039
telemt_connections_me_current 3039
telemt_handshake_timeouts_total 32861
telemt_upstream_connect_attempt_total 3030
telemt_upstream_connect_success_total 3014
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1946
telemt_me_reconnect_success_total 1929
telemt_me_reader_eof_total 2050
telemt_me_idle_close_by_peer_total 2050
telemt_me_route_drop_no_conn_total 609161
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1201187
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5678
telemt_desync_full_logged_total 1762
telemt_desync_suppressed_total 3916
telemt_desync_frames_bucket_total{bucket="1_2"} 1413
telemt_desync_frames_bucket_total{bucket="3_10"} 2146
telemt_desync_frames_bucket_total{bucket="gt_10"} 2119
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 1977
telemt_me_writer_restored_same_endpoint_total 1912
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 1200390
telemt_user_connections_current{user="hello"} 3039
telemt_user_octets_from_client{user="hello"} 26097091368 (24.30 GB)
telemt_user_octets_to_client{user="hello"} 588892798892 (548.45 GB)
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 369
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 21646.4 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2140372
telemt_connections_bad_total 55382
telemt_connections_current 2436
telemt_connections_me_current 2436
telemt_handshake_timeouts_total 21723
telemt_upstream_connect_attempt_total 3262
telemt_upstream_connect_success_total 3230
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 3262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2153
telemt_me_reconnect_success_total 2127
telemt_me_reader_eof_total 2208
telemt_me_idle_close_by_peer_total 2207
telemt_me_route_drop_no_conn_total 3669229
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1914682
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7108
telemt_desync_full_logged_total 1825
telemt_desync_suppressed_total 5283
telemt_desync_frames_bucket_total{bucket="1_2"} 1554
telemt_desync_frames_bucket_total{bucket="3_10"} 3318
telemt_desync_frames_bucket_total{bucket="gt_10"} 2236
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2141
telemt_me_writer_restored_same_endpoint_total 2116
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 1914590
telemt_user_connections_current{user="hello"} 2436
telemt_user_octets_from_client{user="hello"} 17555072556 (16.35 GB)
telemt_user_octets_to_client{user="hello"} 321335028728 (299.27 GB)
telemt_user_unique_ips_current{user="hello"} 799
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16161.6 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1173503
telemt_connections_bad_total 216705
telemt_handshake_timeouts_total 11248
telemt_upstream_connect_attempt_total 2851
telemt_upstream_connect_success_total 2764
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 2851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 4044
telemt_me_reconnect_success_total 1948
telemt_me_reader_eof_total 2069
telemt_me_idle_close_by_peer_total 2069
telemt_me_route_drop_no_conn_total 500304
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 855998
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3025
telemt_desync_full_logged_total 1087
telemt_desync_suppressed_total 1938
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 1037
telemt_desync_frames_bucket_total{bucket="gt_10"} 1423
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2047
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1922
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 855367
telemt_user_connections_current{user="hello"} 3051
telemt_user_octets_from_client{user="hello"} 14918645772 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 404010864500 (376.26 GB)
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 367
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 21095.1 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344035
telemt_connections_bad_total 10658
telemt_connections_current 631
telemt_connections_me_current 631
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3877
telemt_upstream_connect_attempt_total 7692
telemt_upstream_connect_success_total 7660
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 332221
telemt_me_reconnect_success_total 2751
telemt_me_reader_eof_total 2802
telemt_me_idle_close_by_peer_total 2802
telemt_me_route_drop_no_conn_total 208732
telemt_me_route_drop_channel_closed_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305205
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 612
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 387
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 19
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2708
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2740
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 308890
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 5831705537 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 69106346453 (64.36 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 20165.9 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1194834
telemt_connections_bad_total 98237
telemt_connections_current 2867
telemt_connections_me_current 2867
telemt_handshake_timeouts_total 23974
telemt_upstream_connect_attempt_total 3377
telemt_upstream_connect_success_total 3376
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17853
telemt_me_reconnect_success_total 2333
telemt_me_reader_eof_total 2377
telemt_me_idle_close_by_peer_total 2377
telemt_me_route_drop_no_conn_total 544474
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993810
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4270
telemt_desync_full_logged_total 1438
telemt_desync_suppressed_total 2832
telemt_desync_frames_bucket_total{bucket="1_2"} 962
telemt_desync_frames_bucket_total{bucket="3_10"} 1484
telemt_desync_frames_bucket_total{bucket="gt_10"} 1824
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2313
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2272
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 992592
telemt_user_connections_current{user="hello"} 2867
telemt_user_octets_from_client{user="hello"} 19966438240 (18.60 GB)
telemt_user_octets_to_client{user="hello"} 568472282408 (529.43 GB)
telemt_user_unique_ips_current{user="hello"} 825
telemt_user_unique_ips_recent_window{user="hello"} 298
```