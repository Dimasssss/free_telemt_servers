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

# Server Metrics 2026-03-12 15:47:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29636.5 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157477
telemt_connections_bad_total 2021
telemt_handshake_timeouts_total 4724
telemt_upstream_connect_attempt_total 7116
telemt_upstream_connect_success_total 7089
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 5616
telemt_me_reconnect_success_total 5576
telemt_me_reader_eof_total 5874
telemt_me_idle_close_by_peer_total 5873
telemt_me_route_drop_no_conn_total 45486
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135723
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 601
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 375
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5627
telemt_me_writer_restored_same_endpoint_total 5560
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 135689
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 2268706260 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 51605850952 (48.06 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 29529.5 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66067
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 483
telemt_upstream_connect_attempt_total 9436
telemt_upstream_connect_success_total 9239
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 9436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 25729
telemt_me_reconnect_success_total 7746
telemt_me_reader_eof_total 8465
telemt_me_idle_close_by_peer_total 8465
telemt_me_route_drop_no_conn_total 28655
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62799
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 8362
telemt_me_refill_failed_total 561
telemt_me_writer_restored_same_endpoint_total 7731
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 62790
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 704462468 (671.83 MB)
telemt_user_octets_to_client{user="hello"} 17773966484 (16.55 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 29493.0 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89661
telemt_connections_bad_total 1435
telemt_handshake_timeouts_total 1728
telemt_upstream_connect_attempt_total 8096
telemt_upstream_connect_success_total 8096
telemt_upstream_connect_attempts_per_request{bucket="1"} 8096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6616
telemt_me_reconnect_success_total 6559
telemt_me_reader_eof_total 6940
telemt_me_idle_close_by_peer_total 6940
telemt_me_route_drop_no_conn_total 32954
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82765
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6615
telemt_me_writer_restored_same_endpoint_total 6539
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 82738
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 2103854940 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 43461172840 (40.48 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 29468.7 (8h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123433
telemt_connections_bad_total 13035
telemt_handshake_timeouts_total 879
telemt_upstream_connect_attempt_total 6984
telemt_upstream_connect_success_total 6786
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 6984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 301
telemt_me_reconnect_attempts_total 26489
telemt_me_reconnect_success_total 5283
telemt_me_reader_eof_total 6080
telemt_me_idle_close_by_peer_total 6080
telemt_me_route_drop_no_conn_total 42715
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103045
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 369
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 257
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6007
telemt_me_refill_failed_total 661
telemt_me_writer_restored_same_endpoint_total 5275
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 724
telemt_user_connections_total{user="hello"} 102926
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 2007729868 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 43287258864 (40.31 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29438.1 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69366
telemt_connections_bad_total 5702
telemt_handshake_timeouts_total 1075
telemt_upstream_connect_attempt_total 32590
telemt_upstream_connect_success_total 32230
telemt_upstream_connect_fail_total 360
telemt_upstream_connect_attempts_per_request{bucket="1"} 32590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 360
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 39663
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4805
telemt_me_idle_close_by_peer_total 4805
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12695
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33932
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4831
telemt_me_refill_failed_total 1127
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1147
telemt_user_connections_total{user="hello"} 60977
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 537946277 (513.03 MB)
telemt_user_octets_to_client{user="hello"} 18543373066 (17.27 GB)
telemt_user_msgs_from_client{user="hello"} 434996
telemt_user_msgs_to_client{user="hello"} 1764467
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 29426.0 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183077
telemt_connections_bad_total 909
telemt_handshake_timeouts_total 1435
telemt_upstream_connect_attempt_total 6192
telemt_upstream_connect_success_total 6159
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 336
telemt_me_reconnect_attempts_total 5727
telemt_me_reconnect_success_total 4663
telemt_me_reader_eof_total 4929
telemt_me_idle_close_by_peer_total 4928
telemt_me_route_drop_no_conn_total 71092
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175289
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4754
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4656
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 175245
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 3447800388 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 78944409256 (73.52 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 52
```