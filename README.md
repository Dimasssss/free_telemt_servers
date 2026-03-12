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

# Server Metrics 2026-03-12 15:42:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29329.1 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155741
telemt_connections_bad_total 2014
telemt_handshake_timeouts_total 4718
telemt_upstream_connect_attempt_total 7087
telemt_upstream_connect_success_total 7060
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 5587
telemt_me_reconnect_success_total 5547
telemt_me_reader_eof_total 5843
telemt_me_idle_close_by_peer_total 5842
telemt_me_route_drop_no_conn_total 44938
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134271
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
telemt_me_writer_removed_unexpected_total 5596
telemt_me_writer_restored_same_endpoint_total 5531
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 134237
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 2249887256 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 51255750504 (47.74 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 29222.6 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65533
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 483
telemt_upstream_connect_attempt_total 9310
telemt_upstream_connect_success_total 9113
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 9310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 25603
telemt_me_reconnect_success_total 7620
telemt_me_reader_eof_total 8339
telemt_me_idle_close_by_peer_total 8339
telemt_me_route_drop_no_conn_total 28406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62293
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
telemt_me_writer_removed_unexpected_total 8236
telemt_me_refill_failed_total 561
telemt_me_writer_restored_same_endpoint_total 7605
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 62284
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 702158924 (669.63 MB)
telemt_user_octets_to_client{user="hello"} 17702452324 (16.49 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 29185.9 (8h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88846
telemt_connections_bad_total 1435
telemt_handshake_timeouts_total 1723
telemt_upstream_connect_attempt_total 8051
telemt_upstream_connect_success_total 8051
telemt_upstream_connect_attempts_per_request{bucket="1"} 8051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6571
telemt_me_reconnect_success_total 6514
telemt_me_reader_eof_total 6893
telemt_me_idle_close_by_peer_total 6893
telemt_me_route_drop_no_conn_total 32555
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81991
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
telemt_me_writer_removed_unexpected_total 6568
telemt_me_writer_restored_same_endpoint_total 6494
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 81964
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 2099708932 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 43423515568 (40.44 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 29161.4 (8h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122182
telemt_connections_bad_total 13035
telemt_handshake_timeouts_total 842
telemt_upstream_connect_attempt_total 6974
telemt_upstream_connect_success_total 6776
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 6974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 300
telemt_me_reconnect_attempts_total 26479
telemt_me_reconnect_success_total 5273
telemt_me_reader_eof_total 6070
telemt_me_idle_close_by_peer_total 6070
telemt_me_route_drop_no_conn_total 42171
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101867
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 254
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5997
telemt_me_refill_failed_total 661
telemt_me_writer_restored_same_endpoint_total 5265
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 724
telemt_user_connections_total{user="hello"} 101748
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1978166952 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 41888644196 (39.01 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29130.9 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68746
telemt_connections_bad_total 5647
telemt_handshake_timeouts_total 1075
telemt_upstream_connect_attempt_total 32035
telemt_upstream_connect_success_total 31675
telemt_upstream_connect_fail_total 360
telemt_upstream_connect_attempts_per_request{bucket="1"} 32035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 360
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 39663
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4805
telemt_me_idle_close_by_peer_total 4805
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12670
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
telemt_user_connections_total{user="hello"} 60422
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 534473049 (509.71 MB)
telemt_user_octets_to_client{user="hello"} 18514387999 (17.24 GB)
telemt_user_msgs_from_client{user="hello"} 428656
telemt_user_msgs_to_client{user="hello"} 1751728
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 29118.1 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181324
telemt_connections_bad_total 904
telemt_handshake_timeouts_total 1421
telemt_upstream_connect_attempt_total 6155
telemt_upstream_connect_success_total 6122
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 336
telemt_me_reconnect_attempts_total 5690
telemt_me_reconnect_success_total 4626
telemt_me_reader_eof_total 4891
telemt_me_idle_close_by_peer_total 4890
telemt_me_route_drop_no_conn_total 70466
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173602
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 250
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4716
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4619
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 173560
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 3419073652 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 78348435008 (72.97 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 59
```