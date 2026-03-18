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

# Server Metrics 2026-03-18 23:34:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 6387.4 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74672
telemt_connections_bad_total 7460
telemt_connections_current 676
telemt_connections_me_current 676
telemt_handshake_timeouts_total 773
telemt_upstream_connect_attempt_total 1172
telemt_upstream_connect_success_total 1154
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 1171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 803
telemt_me_reconnect_success_total 801
telemt_me_reader_eof_total 813
telemt_me_idle_close_by_peer_total 813
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 25392
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64874
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 341
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 798
telemt_me_writer_restored_same_endpoint_total 790
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 62118
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 645888796 (615.97 MB)
telemt_user_octets_to_client{user="hello"} 27274574724 (25.40 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 6391.3 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172451
telemt_connections_bad_total 13334
telemt_connections_current 1532
telemt_connections_me_current 1532
telemt_handshake_timeouts_total 1408
telemt_upstream_connect_attempt_total 1220
telemt_upstream_connect_success_total 1189
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 1220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 826
telemt_me_reconnect_success_total 825
telemt_me_reader_eof_total 853
telemt_me_idle_close_by_peer_total 853
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 53981
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148391
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 593
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 841
telemt_me_writer_restored_same_endpoint_total 814
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 148471
telemt_user_connections_current{user="hello"} 1532
telemt_user_octets_from_client{user="hello"} 10154514204 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 56748908352 (52.85 GB)
telemt_user_unique_ips_current{user="hello"} 611
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 6388.4 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135300
telemt_connections_bad_total 20115
telemt_connections_current 1128
telemt_connections_me_current 1128
telemt_handshake_timeouts_total 3976
telemt_upstream_connect_attempt_total 1238
telemt_upstream_connect_success_total 1238
telemt_upstream_connect_attempts_per_request{bucket="1"} 1238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 603
telemt_me_reconnect_attempts_total 870
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 46743
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107520
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 469
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 880
telemt_me_writer_restored_same_endpoint_total 853
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 107521
telemt_user_connections_current{user="hello"} 1128
telemt_user_octets_from_client{user="hello"} 1426080404 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 67414829568 (62.78 GB)
telemt_user_unique_ips_current{user="hello"} 513
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 6441.7 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147999
telemt_connections_bad_total 23718
telemt_connections_current 1013
telemt_connections_me_current 1013
telemt_handshake_timeouts_total 3102
telemt_upstream_connect_attempt_total 1168
telemt_upstream_connect_success_total 1168
telemt_upstream_connect_attempts_per_request{bucket="1"} 1168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 802
telemt_me_reconnect_success_total 798
telemt_me_reader_eof_total 819
telemt_me_idle_close_by_peer_total 819
telemt_me_route_drop_no_conn_total 58849
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113291
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 273
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_restored_same_endpoint_total 774
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 113220
telemt_user_connections_current{user="hello"} 1013
telemt_user_octets_from_client{user="hello"} 1170407500 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 42555639256 (39.63 GB)
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 6385.2 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148435
telemt_connections_bad_total 6622
telemt_connections_current 1322
telemt_connections_me_current 1322
telemt_handshake_timeouts_total 4742
telemt_upstream_connect_attempt_total 1180
telemt_upstream_connect_success_total 1173
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 811
telemt_me_reconnect_success_total 807
telemt_me_reader_eof_total 821
telemt_me_idle_close_by_peer_total 821
telemt_me_route_drop_no_conn_total 45591
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117216
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 504
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 809
telemt_me_writer_restored_same_endpoint_total 783
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 117161
telemt_user_connections_current{user="hello"} 1322
telemt_user_octets_from_client{user="hello"} 1518806048 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 73710355968 (68.65 GB)
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 6397.0 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34171
telemt_connections_bad_total 6208
telemt_connections_current 363
telemt_connections_me_current 363
telemt_handshake_timeouts_total 93
telemt_upstream_connect_attempt_total 2053
telemt_upstream_connect_success_total 1993
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 2052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 976
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 3463
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1666
telemt_me_idle_close_by_peer_total 1666
telemt_me_route_drop_no_conn_total 11836
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27112
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
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1669
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 1607
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 27113
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 325205176 (310.14 MB)
telemt_user_octets_to_client{user="hello"} 21884897584 (20.38 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 6387.5 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110020
telemt_connections_bad_total 14367
telemt_connections_current 1142
telemt_connections_me_current 1142
telemt_handshake_timeouts_total 3751
telemt_upstream_connect_attempt_total 1219
telemt_upstream_connect_success_total 1219
telemt_upstream_connect_attempts_per_request{bucket="1"} 1219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 849
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 33491
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89659
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 648
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 860
telemt_me_writer_restored_same_endpoint_total 834
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 89684
telemt_user_connections_current{user="hello"} 1142
telemt_user_octets_from_client{user="hello"} 933246404 (890.01 MB)
telemt_user_octets_to_client{user="hello"} 50323964016 (46.87 GB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 116
```