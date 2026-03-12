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

# Server Metrics 2026-03-12 15:26:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 28407.7 (7h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151049
telemt_connections_bad_total 1941
telemt_handshake_timeouts_total 4613
telemt_upstream_connect_attempt_total 6896
telemt_upstream_connect_success_total 6869
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 277
telemt_me_reconnect_attempts_total 5440
telemt_me_reconnect_success_total 5400
telemt_me_reader_eof_total 5687
telemt_me_idle_close_by_peer_total 5686
telemt_me_route_drop_no_conn_total 43570
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130559
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 596
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5449
telemt_me_writer_restored_same_endpoint_total 5384
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 130525
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 2199546460 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 49364974572 (45.97 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28300.8 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63579
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 441
telemt_upstream_connect_attempt_total 8851
telemt_upstream_connect_success_total 8660
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 8851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 24137
telemt_me_reconnect_success_total 7210
telemt_me_reader_eof_total 7896
telemt_me_idle_close_by_peer_total 7896
telemt_me_route_drop_no_conn_total 27755
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60535
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
telemt_me_writer_removed_unexpected_total 7793
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 7195
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 60526
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 684586788 (652.87 MB)
telemt_user_octets_to_client{user="hello"} 17062870800 (15.89 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 28264.1 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85974
telemt_connections_bad_total 1434
telemt_handshake_timeouts_total 1636
telemt_upstream_connect_attempt_total 7845
telemt_upstream_connect_success_total 7845
telemt_upstream_connect_attempts_per_request{bucket="1"} 7845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 6409
telemt_me_reconnect_success_total 6352
telemt_me_reader_eof_total 6720
telemt_me_idle_close_by_peer_total 6720
telemt_me_route_drop_no_conn_total 31363
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79307
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6404
telemt_me_writer_restored_same_endpoint_total 6332
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 79280
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 2078010024 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 43120139232 (40.16 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28240.1 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117148
telemt_connections_bad_total 11153
telemt_handshake_timeouts_total 803
telemt_upstream_connect_attempt_total 6894
telemt_upstream_connect_success_total 6699
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 6894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 25070
telemt_me_reconnect_success_total 5241
telemt_me_reader_eof_total 5995
telemt_me_idle_close_by_peer_total 5995
telemt_me_route_drop_no_conn_total 40795
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98950
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 338
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5922
telemt_me_refill_failed_total 618
telemt_me_writer_restored_same_endpoint_total 5233
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 681
telemt_user_connections_total{user="hello"} 98831
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 1922044836 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 41101038316 (38.28 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 28209.5 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66230
telemt_connections_bad_total 5455
telemt_handshake_timeouts_total 1065
telemt_upstream_connect_attempt_total 30045
telemt_upstream_connect_success_total 29696
telemt_upstream_connect_fail_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 30045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 349
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 38287
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4762
telemt_me_idle_close_by_peer_total 4762
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12604
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33591
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
telemt_me_writer_removed_unexpected_total 4788
telemt_me_refill_failed_total 1084
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1104
telemt_user_connections_total{user="hello"} 58145
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 496178877 (473.19 MB)
telemt_user_octets_to_client{user="hello"} 17764544816 (16.54 GB)
telemt_user_msgs_from_client{user="hello"} 386077
telemt_user_msgs_to_client{user="hello"} 1642217
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28196.9 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175475
telemt_connections_bad_total 902
telemt_handshake_timeouts_total 1408
telemt_upstream_connect_attempt_total 5940
telemt_upstream_connect_success_total 5908
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 331
telemt_me_reconnect_attempts_total 5519
telemt_me_reconnect_success_total 4456
telemt_me_reader_eof_total 4706
telemt_me_idle_close_by_peer_total 4705
telemt_me_route_drop_no_conn_total 68405
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167871
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4546
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4449
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 167830
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 3351684968 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 76634584304 (71.37 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 63
```