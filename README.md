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

# Server Metrics 2026-03-19 04:10:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 22949.9 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306545
telemt_connections_bad_total 33949
telemt_connections_current 962
telemt_connections_me_current 962
telemt_handshake_timeouts_total 18871
telemt_upstream_connect_attempt_total 4524
telemt_upstream_connect_success_total 4454
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 4524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3314
telemt_me_reconnect_success_total 3298
telemt_me_reader_eof_total 3469
telemt_me_idle_close_by_peer_total 3469
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 78992
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226933
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1630
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1186
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 673
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3323
telemt_me_writer_restored_same_endpoint_total 3281
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 224180
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 2490968444 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 66821254168 (62.23 GB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 22953.9 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562043
telemt_connections_bad_total 38710
telemt_connections_current 2386
telemt_connections_me_current 2386
telemt_handshake_timeouts_total 15601
telemt_upstream_connect_attempt_total 4334
telemt_upstream_connect_success_total 4256
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 4334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 3107
telemt_me_reconnect_success_total 3091
telemt_me_reader_eof_total 3259
telemt_me_idle_close_by_peer_total 3259
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 168495
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 462922
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1747
telemt_desync_full_logged_total 599
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 649
telemt_desync_frames_bucket_total{bucket="gt_10"} 732
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3140
telemt_me_writer_restored_same_endpoint_total 3073
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 462873
telemt_user_connections_current{user="hello"} 2386
telemt_user_octets_from_client{user="hello"} 13515979264 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 202698154704 (188.78 GB)
telemt_user_unique_ips_current{user="hello"} 895
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 22950.8 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463050
telemt_connections_bad_total 97575
telemt_connections_current 1797
telemt_connections_me_current 1797
telemt_handshake_timeouts_total 13253
telemt_upstream_connect_attempt_total 4279
telemt_upstream_connect_success_total 4279
telemt_upstream_connect_attempts_per_request{bucket="1"} 4279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 3129
telemt_me_reconnect_success_total 3119
telemt_me_reader_eof_total 3302
telemt_me_idle_close_by_peer_total 3302
telemt_me_route_drop_no_conn_total 139005
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336987
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1616
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1004
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 661
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3170
telemt_me_writer_restored_same_endpoint_total 3103
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 336983
telemt_user_connections_current{user="hello"} 1797
telemt_user_octets_from_client{user="hello"} 7159054912 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 211057799500 (196.56 GB)
telemt_user_unique_ips_current{user="hello"} 681
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 23004.1 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560542
telemt_connections_bad_total 67387
telemt_connections_current 1589
telemt_connections_me_current 1589
telemt_handshake_timeouts_total 10956
telemt_upstream_connect_attempt_total 4155
telemt_upstream_connect_success_total 4155
telemt_upstream_connect_attempts_per_request{bucket="1"} 4155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 3007
telemt_me_reconnect_success_total 2996
telemt_me_reader_eof_total 3158
telemt_me_idle_close_by_peer_total 3157
telemt_me_route_drop_no_conn_total 140004
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337251
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 944
telemt_desync_full_logged_total 345
telemt_desync_suppressed_total 599
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 411
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3030
telemt_me_writer_restored_same_endpoint_total 2972
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 337002
telemt_user_connections_current{user="hello"} 1589
telemt_user_octets_from_client{user="hello"} 4125279328 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 127533494116 (118.77 GB)
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 22947.7 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 615306
telemt_connections_bad_total 162022
telemt_connections_current 1875
telemt_connections_me_current 1875
telemt_handshake_timeouts_total 18459
telemt_upstream_connect_attempt_total 4291
telemt_upstream_connect_success_total 4263
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3114
telemt_me_reconnect_success_total 3096
telemt_me_reader_eof_total 3270
telemt_me_idle_close_by_peer_total 3270
telemt_me_route_drop_no_conn_total 153944
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367481
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1595
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 978
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3125
telemt_me_writer_restored_same_endpoint_total 3072
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 367399
telemt_user_connections_current{user="hello"} 1875
telemt_user_octets_from_client{user="hello"} 11119688744 (10.36 GB)
telemt_user_octets_to_client{user="hello"} 213124915148 (198.49 GB)
telemt_user_unique_ips_current{user="hello"} 759
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 22959.1 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111469
telemt_connections_bad_total 10212
telemt_connections_current 460
telemt_connections_me_current 460
telemt_handshake_timeouts_total 507
telemt_upstream_connect_attempt_total 6331
telemt_upstream_connect_success_total 6154
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 6331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 6836
telemt_me_reconnect_success_total 4997
telemt_me_reader_eof_total 5253
telemt_me_idle_close_by_peer_total 5253
telemt_me_route_drop_no_conn_total 46398
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97098
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5067
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4967
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 97090
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 1861018912 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 62331897256 (58.05 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 22950.0 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354800
telemt_connections_bad_total 37624
telemt_connections_current 1673
telemt_connections_me_current 1673
telemt_handshake_timeouts_total 18669
telemt_upstream_connect_attempt_total 4845
telemt_upstream_connect_success_total 4845
telemt_upstream_connect_attempts_per_request{bucket="1"} 4845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3696
telemt_me_reconnect_success_total 3686
telemt_me_reader_eof_total 3888
telemt_me_idle_close_by_peer_total 3888
telemt_me_route_drop_no_conn_total 100844
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287423
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1471
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 916
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 580
telemt_desync_frames_bucket_total{bucket="gt_10"} 597
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3725
telemt_me_writer_restored_same_endpoint_total 3671
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 287441
telemt_user_connections_current{user="hello"} 1673
telemt_user_octets_from_client{user="hello"} 3124924592 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 161504957536 (150.41 GB)
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 187
```