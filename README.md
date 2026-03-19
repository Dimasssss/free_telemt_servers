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

# Server Metrics 2026-03-19 07:14:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 33987.5 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 579933
telemt_connections_bad_total 60537
telemt_connections_current 1283
telemt_connections_me_current 1283
telemt_handshake_timeouts_total 23392
telemt_upstream_connect_attempt_total 6569
telemt_upstream_connect_success_total 6448
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 6569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 5901
telemt_me_reconnect_success_total 4750
telemt_me_reader_eof_total 5037
telemt_me_idle_close_by_peer_total 5036
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 163118
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434438
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2856
telemt_desync_full_logged_total 806
telemt_desync_suppressed_total 2050
telemt_desync_frames_bucket_total{bucket="1_2"} 1021
telemt_desync_frames_bucket_total{bucket="3_10"} 1070
telemt_desync_frames_bucket_total{bucket="gt_10"} 765
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4839
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4733
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 431565
telemt_user_connections_current{user="hello"} 1283
telemt_user_octets_from_client{user="hello"} 5852722616 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 145581385656 (135.58 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 33991.5 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1333462
telemt_connections_bad_total 76621
telemt_connections_current 3832
telemt_connections_me_current 3832
telemt_handshake_timeouts_total 32086
telemt_upstream_connect_attempt_total 6386
telemt_upstream_connect_success_total 6264
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 6386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 5709
telemt_me_reconnect_success_total 4555
telemt_me_reader_eof_total 4831
telemt_me_idle_close_by_peer_total 4831
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 568458
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1098478
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4802
telemt_desync_full_logged_total 1629
telemt_desync_suppressed_total 3173
telemt_desync_frames_bucket_total{bucket="1_2"} 880
telemt_desync_frames_bucket_total{bucket="3_10"} 1792
telemt_desync_frames_bucket_total{bucket="gt_10"} 2130
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4676
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4534
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 1098403
telemt_user_connections_current{user="hello"} 3832
telemt_user_octets_from_client{user="hello"} 21062013616 (19.62 GB)
telemt_user_octets_to_client{user="hello"} 450321645324 (419.39 GB)
telemt_user_unique_ips_current{user="hello"} 1319
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 33988.5 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1136652
telemt_connections_bad_total 165442
telemt_connections_current 3057
telemt_connections_me_current 3057
telemt_handshake_timeouts_total 31468
telemt_upstream_connect_attempt_total 6132
telemt_upstream_connect_success_total 6132
telemt_upstream_connect_attempts_per_request{bucket="1"} 6132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4449
telemt_me_reconnect_success_total 4427
telemt_me_reader_eof_total 4683
telemt_me_idle_close_by_peer_total 4683
telemt_me_route_drop_no_conn_total 495865
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851613
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3973
telemt_desync_full_logged_total 1256
telemt_desync_suppressed_total 2717
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 1430
telemt_desync_frames_bucket_total{bucket="gt_10"} 1765
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4507
telemt_me_writer_restored_same_endpoint_total 4411
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 851260
telemt_user_connections_current{user="hello"} 3057
telemt_user_octets_from_client{user="hello"} 15091957328 (14.06 GB)
telemt_user_octets_to_client{user="hello"} 435060444200 (405.18 GB)
telemt_user_unique_ips_current{user="hello"} 998
telemt_user_unique_ips_recent_window{user="hello"} 436
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 34041.9 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1172605
telemt_connections_bad_total 89477
telemt_connections_current 2817
telemt_connections_me_current 2817
telemt_handshake_timeouts_total 29775
telemt_upstream_connect_attempt_total 5941
telemt_upstream_connect_success_total 5941
telemt_upstream_connect_attempts_per_request{bucket="1"} 5941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5284
telemt_me_reconnect_success_total 4223
telemt_me_reader_eof_total 4491
telemt_me_idle_close_by_peer_total 4490
telemt_me_route_drop_no_conn_total 420274
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 807516
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3047
telemt_desync_full_logged_total 1074
telemt_desync_suppressed_total 1973
telemt_desync_frames_bucket_total{bucket="1_2"} 557
telemt_desync_frames_bucket_total{bucket="3_10"} 1209
telemt_desync_frames_bucket_total{bucket="gt_10"} 1281
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4317
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4199
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 806362
telemt_user_connections_current{user="hello"} 2817
telemt_user_octets_from_client{user="hello"} 11897113300 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 289810979828 (269.91 GB)
telemt_user_unique_ips_current{user="hello"} 955
telemt_user_unique_ips_recent_window{user="hello"} 421
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 33985.1 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1437691
telemt_connections_bad_total 411256
telemt_connections_current 3227
telemt_connections_me_current 3227
telemt_handshake_timeouts_total 31575
telemt_upstream_connect_attempt_total 5986
telemt_upstream_connect_success_total 5949
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 5986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4278
telemt_me_reconnect_success_total 4246
telemt_me_reader_eof_total 4495
telemt_me_idle_close_by_peer_total 4495
telemt_me_route_drop_no_conn_total 356729
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 855632
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4269
telemt_desync_full_logged_total 1330
telemt_desync_suppressed_total 2939
telemt_desync_frames_bucket_total{bucket="1_2"} 953
telemt_desync_frames_bucket_total{bucket="3_10"} 1920
telemt_desync_frames_bucket_total{bucket="gt_10"} 1396
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4300
telemt_me_writer_restored_same_endpoint_total 4222
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 855347
telemt_user_connections_current{user="hello"} 3227
telemt_user_octets_from_client{user="hello"} 18920645980 (17.62 GB)
telemt_user_octets_to_client{user="hello"} 430882561300 (401.29 GB)
telemt_user_unique_ips_current{user="hello"} 1115
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 33997.1 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239872
telemt_connections_bad_total 12959
telemt_connections_current 822
telemt_connections_me_current 822
telemt_handshake_timeouts_total 2126
telemt_upstream_connect_attempt_total 8974
telemt_upstream_connect_success_total 8744
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 8974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12412
telemt_me_reconnect_success_total 7039
telemt_me_reader_eof_total 7471
telemt_me_idle_close_by_peer_total 7471
telemt_me_route_drop_no_conn_total 113542
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212340
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 343
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7247
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7009
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 212319
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 3308573620 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 108023179496 (100.60 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 33987.9 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 900604
telemt_connections_bad_total 89797
telemt_connections_current 3019
telemt_connections_me_current 3019
telemt_handshake_timeouts_total 38556
telemt_upstream_connect_attempt_total 6939
telemt_upstream_connect_success_total 6939
telemt_upstream_connect_attempts_per_request{bucket="1"} 6939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6569
telemt_me_reconnect_success_total 5237
telemt_me_reader_eof_total 5549
telemt_me_idle_close_by_peer_total 5549
telemt_me_route_drop_no_conn_total 364347
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738172
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4245
telemt_desync_full_logged_total 1442
telemt_desync_suppressed_total 2803
telemt_desync_frames_bucket_total{bucket="1_2"} 861
telemt_desync_frames_bucket_total{bucket="3_10"} 1619
telemt_desync_frames_bucket_total{bucket="gt_10"} 1765
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5334
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5222
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 737928
telemt_user_connections_current{user="hello"} 3019
telemt_user_octets_from_client{user="hello"} 10761915312 (10.02 GB)
telemt_user_octets_to_client{user="hello"} 410240898476 (382.07 GB)
telemt_user_unique_ips_current{user="hello"} 954
telemt_user_unique_ips_recent_window{user="hello"} 395
```