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

# Server Metrics 2026-03-18 23:40:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 6694.3 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78024
telemt_connections_bad_total 7920
telemt_connections_current 675
telemt_connections_me_current 675
telemt_handshake_timeouts_total 816
telemt_upstream_connect_attempt_total 1253
telemt_upstream_connect_success_total 1234
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 871
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 889
telemt_me_idle_close_by_peer_total 889
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 26095
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67597
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 356
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 866
telemt_me_writer_restored_same_endpoint_total 858
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 64841
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 662311544 (631.63 MB)
telemt_user_octets_to_client{user="hello"} 28438595568 (26.49 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 6697.9 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177715
telemt_connections_bad_total 13409
telemt_connections_current 1561
telemt_connections_me_current 1561
telemt_handshake_timeouts_total 1477
telemt_upstream_connect_attempt_total 1299
telemt_upstream_connect_success_total 1266
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 1299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 896
telemt_me_reconnect_success_total 895
telemt_me_reader_eof_total 930
telemt_me_idle_close_by_peer_total 930
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 56375
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153208
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 627
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 911
telemt_me_writer_restored_same_endpoint_total 884
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 153287
telemt_user_connections_current{user="hello"} 1561
telemt_user_octets_from_client{user="hello"} 10196099716 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 58777553468 (54.74 GB)
telemt_user_unique_ips_current{user="hello"} 617
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 6695.2 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139519
telemt_connections_bad_total 20877
telemt_connections_current 1070
telemt_connections_me_current 1070
telemt_handshake_timeouts_total 4147
telemt_upstream_connect_attempt_total 1307
telemt_upstream_connect_success_total 1307
telemt_upstream_connect_attempts_per_request{bucket="1"} 1307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 643
telemt_me_reconnect_attempts_total 938
telemt_me_reconnect_success_total 937
telemt_me_reader_eof_total 967
telemt_me_idle_close_by_peer_total 967
telemt_me_route_drop_no_conn_total 47936
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110737
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 473
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 948
telemt_me_writer_restored_same_endpoint_total 921
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 110738
telemt_user_connections_current{user="hello"} 1070
telemt_user_octets_from_client{user="hello"} 1445073460 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 69030499664 (64.29 GB)
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 6748.3 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151919
telemt_connections_bad_total 23797
telemt_connections_current 946
telemt_connections_me_current 946
telemt_handshake_timeouts_total 3138
telemt_upstream_connect_attempt_total 1239
telemt_upstream_connect_success_total 1239
telemt_upstream_connect_attempts_per_request{bucket="1"} 1239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 873
telemt_me_reconnect_success_total 870
telemt_me_reader_eof_total 896
telemt_me_idle_close_by_peer_total 896
telemt_me_route_drop_no_conn_total 59926
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116399
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 275
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 883
telemt_me_writer_restored_same_endpoint_total 846
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 116327
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 1182095280 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 43315585648 (40.34 GB)
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 6691.9 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153848
telemt_connections_bad_total 6926
telemt_connections_current 1287
telemt_connections_me_current 1287
telemt_handshake_timeouts_total 4938
telemt_upstream_connect_attempt_total 1252
telemt_upstream_connect_success_total 1245
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 875
telemt_me_reconnect_success_total 871
telemt_me_reader_eof_total 893
telemt_me_idle_close_by_peer_total 893
telemt_me_route_drop_no_conn_total 47446
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121247
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 510
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 873
telemt_me_writer_restored_same_endpoint_total 847
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 121192
telemt_user_connections_current{user="hello"} 1287
telemt_user_octets_from_client{user="hello"} 1563739344 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 77154236548 (71.86 GB)
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 6703.4 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35768
telemt_connections_bad_total 6618
telemt_connections_current 353
telemt_connections_me_current 353
telemt_handshake_timeouts_total 93
telemt_upstream_connect_attempt_total 2134
telemt_upstream_connect_success_total 2073
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 2134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1016
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 3533
telemt_me_reconnect_success_total 1707
telemt_me_reader_eof_total 1763
telemt_me_idle_close_by_peer_total 1763
telemt_me_route_drop_no_conn_total 12236
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28268
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1739
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 1677
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 28269
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 335523572 (319.98 MB)
telemt_user_octets_to_client{user="hello"} 22501648636 (20.96 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 6694.1 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113781
telemt_connections_bad_total 14777
telemt_connections_current 1044
telemt_connections_me_current 1044
telemt_handshake_timeouts_total 3917
telemt_upstream_connect_attempt_total 1296
telemt_upstream_connect_success_total 1296
telemt_upstream_connect_attempts_per_request{bucket="1"} 1296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 926
telemt_me_reconnect_success_total 924
telemt_me_reader_eof_total 955
telemt_me_idle_close_by_peer_total 955
telemt_me_route_drop_no_conn_total 34645
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92812
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 659
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 935
telemt_me_writer_restored_same_endpoint_total 909
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 92837
telemt_user_connections_current{user="hello"} 1044
telemt_user_octets_from_client{user="hello"} 951319740 (907.25 MB)
telemt_user_octets_to_client{user="hello"} 51307626268 (47.78 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 77
```