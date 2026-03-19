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

# Server Metrics 2026-03-19 01:42:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 14055.3 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161688
telemt_connections_bad_total 19902
telemt_connections_current 668
telemt_connections_me_current 668
telemt_handshake_timeouts_total 3784
telemt_upstream_connect_attempt_total 2838
telemt_upstream_connect_success_total 2791
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2083
telemt_me_reconnect_success_total 2077
telemt_me_reader_eof_total 2162
telemt_me_idle_close_by_peer_total 2162
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 47708
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131103
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 830
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 612
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2082
telemt_me_writer_restored_same_endpoint_total 2063
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 128333
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 1331594192 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 42639805032 (39.71 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 14059.3 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313751
telemt_connections_bad_total 21215
telemt_connections_current 1395
telemt_connections_me_current 1395
telemt_handshake_timeouts_total 5665
telemt_upstream_connect_attempt_total 2732
telemt_upstream_connect_success_total 2680
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 2732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 1964
telemt_me_reconnect_success_total 1957
telemt_me_reader_eof_total 2055
telemt_me_idle_close_by_peer_total 2055
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 97696
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268687
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 956
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 630
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1991
telemt_me_writer_restored_same_endpoint_total 1944
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 268728
telemt_user_connections_current{user="hello"} 1395
telemt_user_octets_from_client{user="hello"} 11249424056 (10.48 GB)
telemt_user_octets_to_client{user="hello"} 103085632632 (96.01 GB)
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 14056.6 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252713
telemt_connections_bad_total 47007
telemt_connections_current 1096
telemt_connections_me_current 1096
telemt_handshake_timeouts_total 6356
telemt_upstream_connect_attempt_total 2733
telemt_upstream_connect_success_total 2733
telemt_upstream_connect_attempts_per_request{bucket="1"} 2733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2018
telemt_me_reconnect_success_total 2012
telemt_me_reader_eof_total 2119
telemt_me_idle_close_by_peer_total 2119
telemt_me_route_drop_no_conn_total 78402
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192027
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 921
telemt_desync_full_logged_total 337
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2042
telemt_me_writer_restored_same_endpoint_total 1996
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 192018
telemt_user_connections_current{user="hello"} 1096
telemt_user_octets_from_client{user="hello"} 2351260972 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 114214094432 (106.37 GB)
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 14109.8 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281406
telemt_connections_bad_total 27924
telemt_connections_current 968
telemt_connections_me_current 968
telemt_handshake_timeouts_total 4914
telemt_upstream_connect_attempt_total 2595
telemt_upstream_connect_success_total 2595
telemt_upstream_connect_attempts_per_request{bucket="1"} 2595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1881
telemt_me_reconnect_success_total 1875
telemt_me_reader_eof_total 1963
telemt_me_idle_close_by_peer_total 1963
telemt_me_route_drop_no_conn_total 88534
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194037
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 351
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1895
telemt_me_writer_restored_same_endpoint_total 1851
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 193955
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 1832249352 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 65608671648 (61.10 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 14053.4 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274334
telemt_connections_bad_total 16534
telemt_connections_current 1228
telemt_connections_me_current 1228
telemt_handshake_timeouts_total 9137
telemt_upstream_connect_attempt_total 2649
telemt_upstream_connect_success_total 2635
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1921
telemt_me_reconnect_success_total 1910
telemt_me_reader_eof_total 2003
telemt_me_idle_close_by_peer_total 2003
telemt_me_route_drop_no_conn_total 84819
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209830
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 836
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 296
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1920
telemt_me_writer_restored_same_endpoint_total 1886
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 209753
telemt_user_connections_current{user="hello"} 1228
telemt_user_octets_from_client{user="hello"} 5936227156 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 117445221328 (109.38 GB)
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 14064.8 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68805
telemt_connections_bad_total 9244
telemt_connections_current 264
telemt_connections_me_current 264
telemt_handshake_timeouts_total 249
telemt_upstream_connect_attempt_total 4009
telemt_upstream_connect_success_total 3890
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 4009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2053
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 5004
telemt_me_reconnect_success_total 3174
telemt_me_reader_eof_total 3324
telemt_me_idle_close_by_peer_total 3324
telemt_me_route_drop_no_conn_total 26818
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57473
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3222
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3144
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 57473
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 828882944 (790.48 MB)
telemt_user_octets_to_client{user="hello"} 38286468176 (35.66 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 14055.5 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193932
telemt_connections_bad_total 21951
telemt_connections_current 1026
telemt_connections_me_current 1026
telemt_handshake_timeouts_total 9018
telemt_upstream_connect_attempt_total 3021
telemt_upstream_connect_success_total 3021
telemt_upstream_connect_attempts_per_request{bucket="1"} 3021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2306
telemt_me_reconnect_success_total 2298
telemt_me_reader_eof_total 2413
telemt_me_idle_close_by_peer_total 2413
telemt_me_route_drop_no_conn_total 57726
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158406
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 978
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 588
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 411
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2325
telemt_me_writer_restored_same_endpoint_total 2283
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 158430
telemt_user_connections_current{user="hello"} 1026
telemt_user_octets_from_client{user="hello"} 1633683304 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 83400348012 (77.67 GB)
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 77
```