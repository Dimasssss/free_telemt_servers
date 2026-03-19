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

# Server Metrics 2026-03-19 00:00:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 7922.2 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91381
telemt_connections_bad_total 9716
telemt_connections_current 628
telemt_connections_me_current 628
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 1456
telemt_upstream_connect_success_total 1433
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1027
telemt_me_reconnect_success_total 1024
telemt_me_reader_eof_total 1050
telemt_me_idle_close_by_peer_total 1050
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 29689
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77025
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 414
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1023
telemt_me_writer_restored_same_endpoint_total 1012
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 74270
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 725384800 (691.78 MB)
telemt_user_octets_to_client{user="hello"} 31162674320 (29.02 GB)
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 7925.5 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203316
telemt_connections_bad_total 16112
telemt_connections_current 1548
telemt_connections_me_current 1548
telemt_handshake_timeouts_total 1798
telemt_upstream_connect_attempt_total 1494
telemt_upstream_connect_success_total 1461
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 1494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 1048
telemt_me_reconnect_success_total 1047
telemt_me_reader_eof_total 1091
telemt_me_idle_close_by_peer_total 1091
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 62974
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174191
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 711
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1067
telemt_me_writer_restored_same_endpoint_total 1036
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 174266
telemt_user_connections_current{user="hello"} 1548
telemt_user_octets_from_client{user="hello"} 10473362084 (9.75 GB)
telemt_user_octets_to_client{user="hello"} 66683990272 (62.10 GB)
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 7922.6 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157800
telemt_connections_bad_total 23947
telemt_connections_current 1140
telemt_connections_me_current 1140
telemt_handshake_timeouts_total 4377
telemt_upstream_connect_attempt_total 1535
telemt_upstream_connect_success_total 1535
telemt_upstream_connect_attempts_per_request{bucket="1"} 1535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 758
telemt_me_reconnect_attempts_total 1123
telemt_me_reconnect_success_total 1120
telemt_me_reader_eof_total 1160
telemt_me_idle_close_by_peer_total 1160
telemt_me_route_drop_no_conn_total 53340
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124721
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 527
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 318
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1134
telemt_me_writer_restored_same_endpoint_total 1104
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 124723
telemt_user_connections_current{user="hello"} 1140
telemt_user_octets_from_client{user="hello"} 1708130976 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 75369261264 (70.19 GB)
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 7976.2 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168261
telemt_connections_bad_total 25125
telemt_connections_current 971
telemt_connections_me_current 971
telemt_handshake_timeouts_total 3280
telemt_upstream_connect_attempt_total 1453
telemt_upstream_connect_success_total 1453
telemt_upstream_connect_attempts_per_request{bucket="1"} 1453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1044
telemt_me_reconnect_success_total 1040
telemt_me_reader_eof_total 1074
telemt_me_idle_close_by_peer_total 1074
telemt_me_route_drop_no_conn_total 64584
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129910
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 312
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1053
telemt_me_writer_restored_same_endpoint_total 1016
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 129836
telemt_user_connections_current{user="hello"} 971
telemt_user_octets_from_client{user="hello"} 1462747312 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 49353955116 (45.96 GB)
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 7919.3 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173639
telemt_connections_bad_total 7740
telemt_connections_current 1210
telemt_connections_me_current 1210
telemt_handshake_timeouts_total 6013
telemt_upstream_connect_attempt_total 1440
telemt_upstream_connect_success_total 1432
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1019
telemt_me_reconnect_success_total 1014
telemt_me_reader_eof_total 1043
telemt_me_idle_close_by_peer_total 1043
telemt_me_route_drop_no_conn_total 55569
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135905
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 579
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 346
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_restored_same_endpoint_total 990
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 135850
telemt_user_connections_current{user="hello"} 1210
telemt_user_octets_from_client{user="hello"} 1727771912 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 84813718528 (78.99 GB)
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 7931.1 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41653
telemt_connections_bad_total 7246
telemt_connections_current 413
telemt_connections_me_current 413
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 2466
telemt_upstream_connect_success_total 2394
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 2466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 3810
telemt_me_reconnect_success_total 1983
telemt_me_reader_eof_total 2043
telemt_me_idle_close_by_peer_total 2043
telemt_me_route_drop_no_conn_total 14893
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33309
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
telemt_me_writer_removed_unexpected_total 2019
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 1953
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 33310
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 397997324 (379.56 MB)
telemt_user_octets_to_client{user="hello"} 24351262256 (22.68 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 7921.7 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128833
telemt_connections_bad_total 16483
telemt_connections_current 1156
telemt_connections_me_current 1156
telemt_handshake_timeouts_total 4580
telemt_upstream_connect_attempt_total 1570
telemt_upstream_connect_success_total 1570
telemt_upstream_connect_attempts_per_request{bucket="1"} 1570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1157
telemt_me_reconnect_success_total 1154
telemt_me_reader_eof_total 1195
telemt_me_idle_close_by_peer_total 1195
telemt_me_route_drop_no_conn_total 38770
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105255
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 725
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1166
telemt_me_writer_restored_same_endpoint_total 1139
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 105280
telemt_user_connections_current{user="hello"} 1156
telemt_user_octets_from_client{user="hello"} 1031638320 (983.85 MB)
telemt_user_octets_to_client{user="hello"} 55293974664 (51.50 GB)
telemt_user_unique_ips_current{user="hello"} 468
telemt_user_unique_ips_recent_window{user="hello"} 122
```