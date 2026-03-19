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

# Server Metrics 2026-03-19 04:00:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 22335.8 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287850
telemt_connections_bad_total 32797
telemt_connections_current 898
telemt_connections_me_current 898
telemt_handshake_timeouts_total 18577
telemt_upstream_connect_attempt_total 4389
telemt_upstream_connect_success_total 4321
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 4389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3225
telemt_me_reconnect_success_total 3209
telemt_me_reader_eof_total 3370
telemt_me_idle_close_by_peer_total 3370
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 75686
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218252
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1571
telemt_desync_full_logged_total 428
telemt_desync_suppressed_total 1143
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3232
telemt_me_writer_restored_same_endpoint_total 3192
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 215500
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 2416643120 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 64287744576 (59.87 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 22339.9 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536662
telemt_connections_bad_total 38460
telemt_connections_current 2335
telemt_connections_me_current 2335
telemt_handshake_timeouts_total 15122
telemt_upstream_connect_attempt_total 4217
telemt_upstream_connect_success_total 4143
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 4217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 3036
telemt_me_reconnect_success_total 3022
telemt_me_reader_eof_total 3184
telemt_me_idle_close_by_peer_total 3184
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 159145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440919
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1657
telemt_desync_full_logged_total 566
telemt_desync_suppressed_total 1091
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3067
telemt_me_writer_restored_same_endpoint_total 3004
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 440875
telemt_user_connections_current{user="hello"} 2335
telemt_user_octets_from_client{user="hello"} 13215027828 (12.31 GB)
telemt_user_octets_to_client{user="hello"} 191364204004 (178.22 GB)
telemt_user_unique_ips_current{user="hello"} 858
telemt_user_unique_ips_recent_window{user="hello"} 332
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 22337.2 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438622
telemt_connections_bad_total 92589
telemt_connections_current 1729
telemt_connections_me_current 1729
telemt_handshake_timeouts_total 11836
telemt_upstream_connect_attempt_total 4161
telemt_upstream_connect_success_total 4161
telemt_upstream_connect_attempts_per_request{bucket="1"} 4161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 3054
telemt_me_reconnect_success_total 3044
telemt_me_reader_eof_total 3220
telemt_me_idle_close_by_peer_total 3220
telemt_me_route_drop_no_conn_total 129232
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320131
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1551
telemt_desync_full_logged_total 590
telemt_desync_suppressed_total 961
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 636
telemt_desync_frames_bucket_total{bucket="gt_10"} 653
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3093
telemt_me_writer_restored_same_endpoint_total 3028
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 320128
telemt_user_connections_current{user="hello"} 1729
telemt_user_octets_from_client{user="hello"} 6772056648 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 202314605364 (188.42 GB)
telemt_user_unique_ips_current{user="hello"} 685
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 22390.4 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533114
telemt_connections_bad_total 63110
telemt_connections_current 1615
telemt_connections_me_current 1615
telemt_handshake_timeouts_total 10574
telemt_upstream_connect_attempt_total 4037
telemt_upstream_connect_success_total 4037
telemt_upstream_connect_attempts_per_request{bucket="1"} 4037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2933
telemt_me_reconnect_success_total 2922
telemt_me_reader_eof_total 3080
telemt_me_idle_close_by_peer_total 3079
telemt_me_route_drop_no_conn_total 133067
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320590
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 891
telemt_desync_full_logged_total 324
telemt_desync_suppressed_total 567
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 317
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2956
telemt_me_writer_restored_same_endpoint_total 2898
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 320338
telemt_user_connections_current{user="hello"} 1615
telemt_user_octets_from_client{user="hello"} 3935187596 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 118834219380 (110.67 GB)
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 22333.6 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556972
telemt_connections_bad_total 124904
telemt_connections_current 1837
telemt_connections_me_current 1837
telemt_handshake_timeouts_total 17610
telemt_upstream_connect_attempt_total 4181
telemt_upstream_connect_success_total 4153
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3047
telemt_me_reconnect_success_total 3029
telemt_me_reader_eof_total 3196
telemt_me_idle_close_by_peer_total 3196
telemt_me_route_drop_no_conn_total 146698
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349826
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1525
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 937
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 617
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3056
telemt_me_writer_restored_same_endpoint_total 3005
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 349744
telemt_user_connections_current{user="hello"} 1837
telemt_user_octets_from_client{user="hello"} 10807987748 (10.07 GB)
telemt_user_octets_to_client{user="hello"} 200898150040 (187.10 GB)
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 22345.2 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107223
telemt_connections_bad_total 10134
telemt_connections_current 465
telemt_connections_me_current 465
telemt_handshake_timeouts_total 483
telemt_upstream_connect_attempt_total 6153
telemt_upstream_connect_success_total 5987
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 6153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 6712
telemt_me_reconnect_success_total 4874
telemt_me_reader_eof_total 5128
telemt_me_idle_close_by_peer_total 5128
telemt_me_route_drop_no_conn_total 44591
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93098
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4942
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4844
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 93090
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 1781318248 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 60295865672 (56.15 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 22336.0 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336045
telemt_connections_bad_total 36543
telemt_connections_current 1617
telemt_connections_me_current 1617
telemt_handshake_timeouts_total 17760
telemt_upstream_connect_attempt_total 4695
telemt_upstream_connect_success_total 4695
telemt_upstream_connect_attempts_per_request{bucket="1"} 4695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3591
telemt_me_reconnect_success_total 3581
telemt_me_reader_eof_total 3773
telemt_me_idle_close_by_peer_total 3773
telemt_me_route_drop_no_conn_total 93979
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272686
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1385
telemt_desync_full_logged_total 524
telemt_desync_suppressed_total 861
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3619
telemt_me_writer_restored_same_endpoint_total 3566
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 272704
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 2951024296 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 153080546804 (142.57 GB)
telemt_user_unique_ips_current{user="hello"} 596
telemt_user_unique_ips_recent_window{user="hello"} 232
```