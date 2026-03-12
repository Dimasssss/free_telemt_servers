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

# Server Metrics 2026-03-12 13:39:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21962.4 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116443
telemt_connections_bad_total 1359
telemt_handshake_timeouts_total 3888
telemt_upstream_connect_attempt_total 5337
telemt_upstream_connect_success_total 5313
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 243
telemt_me_reconnect_attempts_total 4195
telemt_me_reconnect_success_total 4168
telemt_me_reader_eof_total 4374
telemt_me_idle_close_by_peer_total 4373
telemt_me_route_drop_no_conn_total 32817
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102678
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 301
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4201
telemt_me_writer_restored_same_endpoint_total 4152
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 102642
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 1654619304 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 39063733912 (36.38 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 21855.7 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47180
telemt_connections_bad_total 336
telemt_handshake_timeouts_total 344
telemt_upstream_connect_attempt_total 6506
telemt_upstream_connect_success_total 6350
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 6506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 21051
telemt_me_reconnect_success_total 5220
telemt_me_reader_eof_total 5809
telemt_me_idle_close_by_peer_total 5809
telemt_me_route_drop_no_conn_total 20463
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45044
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
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
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5743
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5205
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 45041
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 551379772 (525.84 MB)
telemt_user_octets_to_client{user="hello"} 12895552036 (12.01 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 21819.0 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63759
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 711
telemt_upstream_connect_attempt_total 5972
telemt_upstream_connect_success_total 5971
telemt_upstream_connect_attempts_per_request{bucket="1"} 5971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4849
telemt_me_reconnect_success_total 4811
telemt_me_reader_eof_total 5085
telemt_me_idle_close_by_peer_total 5085
telemt_me_route_drop_no_conn_total 22362
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60032
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
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4846
telemt_me_writer_restored_same_endpoint_total 4791
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 60015
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 1817382988 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 35635907468 (33.19 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 21794.6 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82722
telemt_connections_bad_total 1463
telemt_handshake_timeouts_total 373
telemt_upstream_connect_attempt_total 5966
telemt_upstream_connect_success_total 5815
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 5966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 14668
telemt_me_reconnect_success_total 4665
telemt_me_reader_eof_total 5107
telemt_me_idle_close_by_peer_total 5107
telemt_me_route_drop_no_conn_total 31092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75879
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 237
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5031
telemt_me_refill_failed_total 311
telemt_me_writer_restored_same_endpoint_total 4657
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 75763
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 1263853024 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 33677317780 (31.36 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21764.0 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47525
telemt_connections_bad_total 4099
telemt_handshake_timeouts_total 680
telemt_upstream_connect_attempt_total 14966
telemt_upstream_connect_success_total 14699
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 14966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 27944
telemt_me_reconnect_success_total 3663
telemt_me_reader_eof_total 4418
telemt_me_idle_close_by_peer_total 4418
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 11934
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31696
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4443
telemt_me_refill_failed_total 760
telemt_me_writer_restored_same_endpoint_total 3646
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 780
telemt_user_connections_total{user="hello"} 41589
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 339512802 (323.78 MB)
telemt_user_octets_to_client{user="hello"} 10811135936 (10.07 GB)
telemt_user_msgs_from_client{user="hello"} 139940
telemt_user_msgs_to_client{user="hello"} 407221
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 21751.0 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128007
telemt_connections_bad_total 771
telemt_handshake_timeouts_total 985
telemt_upstream_connect_attempt_total 4496
telemt_upstream_connect_success_total 4473
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 3369
telemt_me_reconnect_success_total 3340
telemt_me_reader_eof_total 3519
telemt_me_idle_close_by_peer_total 3519
telemt_me_route_drop_no_conn_total 51273
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122152
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 217
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3380
telemt_me_writer_restored_same_endpoint_total 3333
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 122119
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 2699618076 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 52680871048 (49.06 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 54
```