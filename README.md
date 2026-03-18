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

# Server Metrics 2026-03-18 20:05:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16788.5 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420424
telemt_connections_bad_total 24628
telemt_handshake_timeouts_total 9131
telemt_upstream_connect_attempt_total 3009
telemt_upstream_connect_success_total 3006
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 2159
telemt_me_reconnect_success_total 2146
telemt_me_reader_eof_total 2236
telemt_me_idle_close_by_peer_total 2236
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 177553
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364107
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2159
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1546
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 957
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2187
telemt_me_writer_restored_same_endpoint_total 2128
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 363928
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 7234106928 (6.74 GB)
telemt_user_octets_to_client{user="hello"} 129862632300 (120.94 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 21616.4 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2008835
telemt_connections_bad_total 139636
telemt_connections_current 3251
telemt_connections_me_current 3251
telemt_handshake_timeouts_total 34705
telemt_upstream_connect_attempt_total 3385
telemt_upstream_connect_success_total 3367
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1563
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2303
telemt_me_reconnect_success_total 2286
telemt_me_reader_eof_total 2310
telemt_me_idle_close_by_peer_total 2309
telemt_me_route_drop_no_conn_total 1787939
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1737474
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6058
telemt_desync_full_logged_total 1951
telemt_desync_suppressed_total 4107
telemt_desync_frames_bucket_total{bucket="1_2"} 1044
telemt_desync_frames_bucket_total{bucket="3_10"} 2411
telemt_desync_frames_bucket_total{bucket="gt_10"} 2603
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2245
telemt_me_writer_restored_same_endpoint_total 2284
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1732767
telemt_user_connections_current{user="hello"} 3251
telemt_user_octets_from_client{user="hello"} 26696211568 (24.86 GB)
telemt_user_octets_to_client{user="hello"} 579551611000 (539.75 GB)
telemt_user_unique_ips_current{user="hello"} 1089
telemt_user_unique_ips_recent_window{user="hello"} 386
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 21544.6 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1529770
telemt_connections_bad_total 126330
telemt_connections_current 2858
telemt_connections_me_current 2858
telemt_handshake_timeouts_total 34502
telemt_upstream_connect_attempt_total 3060
telemt_upstream_connect_success_total 3044
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1976
telemt_me_reconnect_success_total 1959
telemt_me_reader_eof_total 2082
telemt_me_idle_close_by_peer_total 2082
telemt_me_route_drop_no_conn_total 620739
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1227780
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5877
telemt_desync_full_logged_total 1811
telemt_desync_suppressed_total 4066
telemt_desync_frames_bucket_total{bucket="1_2"} 1471
telemt_desync_frames_bucket_total{bucket="3_10"} 2219
telemt_desync_frames_bucket_total{bucket="gt_10"} 2187
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2009
telemt_me_writer_restored_same_endpoint_total 1942
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 1226984
telemt_user_connections_current{user="hello"} 2858
telemt_user_octets_from_client{user="hello"} 26604726956 (24.78 GB)
telemt_user_octets_to_client{user="hello"} 606992429232 (565.31 GB)
telemt_user_unique_ips_current{user="hello"} 958
telemt_user_unique_ips_recent_window{user="hello"} 353
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 22259.3 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2167180
telemt_connections_bad_total 57054
telemt_connections_current 2316
telemt_connections_me_current 2316
telemt_handshake_timeouts_total 21899
telemt_upstream_connect_attempt_total 3357
telemt_upstream_connect_success_total 3322
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1584
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2211
telemt_me_reconnect_success_total 2184
telemt_me_reader_eof_total 2272
telemt_me_idle_close_by_peer_total 2271
telemt_me_route_drop_no_conn_total 3684383
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1938456
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7241
telemt_desync_full_logged_total 1863
telemt_desync_suppressed_total 5378
telemt_desync_frames_bucket_total{bucket="1_2"} 1582
telemt_desync_frames_bucket_total{bucket="3_10"} 3365
telemt_desync_frames_bucket_total{bucket="gt_10"} 2294
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2200
telemt_me_writer_restored_same_endpoint_total 2173
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1938364
telemt_user_connections_current{user="hello"} 2316
telemt_user_octets_from_client{user="hello"} 18019459832 (16.78 GB)
telemt_user_octets_to_client{user="hello"} 330534455432 (307.83 GB)
telemt_user_unique_ips_current{user="hello"} 813
telemt_user_unique_ips_recent_window{user="hello"} 294
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16774.4 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1202054
telemt_connections_bad_total 218119
telemt_handshake_timeouts_total 11539
telemt_upstream_connect_attempt_total 3039
telemt_upstream_connect_success_total 2947
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 3038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 4185
telemt_me_reconnect_success_total 2088
telemt_me_reader_eof_total 2212
telemt_me_idle_close_by_peer_total 2212
telemt_me_route_drop_no_conn_total 511212
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879847
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3105
telemt_desync_full_logged_total 1118
telemt_desync_suppressed_total 1987
telemt_desync_frames_bucket_total{bucket="1_2"} 574
telemt_desync_frames_bucket_total{bucket="3_10"} 1060
telemt_desync_frames_bucket_total{bucket="gt_10"} 1471
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2190
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 2062
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 879211
telemt_user_connections_current{user="hello"} 2913
telemt_user_octets_from_client{user="hello"} 15319696096 (14.27 GB)
telemt_user_octets_to_client{user="hello"} 419805870332 (390.97 GB)
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 355
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 21708.2 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349710
telemt_connections_bad_total 10668
telemt_connections_current 666
telemt_connections_me_current 666
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3928
telemt_upstream_connect_attempt_total 7797
telemt_upstream_connect_success_total 7765
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 332283
telemt_me_reconnect_success_total 2813
telemt_me_reader_eof_total 2865
telemt_me_idle_close_by_peer_total 2865
telemt_me_route_drop_no_conn_total 211005
telemt_me_route_drop_channel_closed_total 102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310471
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 644
telemt_desync_full_logged_total 234
telemt_desync_suppressed_total 410
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2770
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2802
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 314156
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 6320746757 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 71600812021 (66.68 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 20778.7 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1222839
telemt_connections_bad_total 99514
telemt_connections_current 2633
telemt_connections_me_current 2633
telemt_handshake_timeouts_total 24783
telemt_upstream_connect_attempt_total 3446
telemt_upstream_connect_success_total 3445
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17889
telemt_me_reconnect_success_total 2369
telemt_me_reader_eof_total 2415
telemt_me_idle_close_by_peer_total 2415
telemt_me_route_drop_no_conn_total 553652
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1018871
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4473
telemt_desync_full_logged_total 1496
telemt_desync_suppressed_total 2977
telemt_desync_frames_bucket_total{bucket="1_2"} 1022
telemt_desync_frames_bucket_total{bucket="3_10"} 1551
telemt_desync_frames_bucket_total{bucket="gt_10"} 1900
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2351
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2308
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1017651
telemt_user_connections_current{user="hello"} 2633
telemt_user_octets_from_client{user="hello"} 20410942384 (19.01 GB)
telemt_user_octets_to_client{user="hello"} 585949539996 (545.71 GB)
telemt_user_unique_ips_current{user="hello"} 829
telemt_user_unique_ips_recent_window{user="hello"} 295
```