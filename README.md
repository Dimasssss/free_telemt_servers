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

# Server Metrics 2026-03-13 04:24:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 75039.6 (20h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286974
telemt_connections_bad_total 3026
telemt_handshake_timeouts_total 5767
telemt_upstream_connect_attempt_total 18982
telemt_upstream_connect_success_total 18896
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 18982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1535
telemt_me_reconnect_attempts_total 18605
telemt_me_reconnect_success_total 15116
telemt_me_reader_eof_total 16160
telemt_me_idle_close_by_peer_total 16159
telemt_me_route_drop_no_conn_total 89476
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240424
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 799
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 501
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 15388
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15100
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 240363
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 4172645016 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 118532931520 (110.39 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 74932.5 (20h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132170
telemt_connections_bad_total 748
telemt_handshake_timeouts_total 986
telemt_upstream_connect_attempt_total 40465
telemt_upstream_connect_success_total 39964
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 40465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 504
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_keepalive_timeout_total 542
telemt_me_reconnect_attempts_total 66260
telemt_me_reconnect_success_total 19698
telemt_me_reader_eof_total 21756
telemt_me_idle_close_by_peer_total 21756
telemt_me_route_drop_no_conn_total 48370
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109082
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 21302
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 19683
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1604
telemt_user_connections_total{user="hello"} 125582
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 1302748600 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 37704203255 (35.11 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 74895.9 (20h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159317
telemt_connections_bad_total 1845
telemt_handshake_timeouts_total 2585
telemt_upstream_connect_attempt_total 20735
telemt_upstream_connect_success_total 20733
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11142
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 417
telemt_me_reconnect_attempts_total 18091
telemt_me_reconnect_success_total 16927
telemt_me_reader_eof_total 18127
telemt_me_idle_close_by_peer_total 18127
telemt_me_route_drop_no_conn_total 61775
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149015
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 17113
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 16907
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 148942
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2808557684 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 69693413824 (64.91 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 74871.7 (20h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229242
telemt_connections_bad_total 13503
telemt_handshake_timeouts_total 1460
telemt_upstream_connect_attempt_total 33216
telemt_upstream_connect_success_total 23352
telemt_upstream_connect_fail_total 9864
telemt_upstream_connect_attempts_per_request{bucket="1"} 33216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9864
telemt_me_keepalive_timeout_total 3308
telemt_me_reconnect_attempts_total 61888
telemt_me_reconnect_success_total 16728
telemt_me_reader_eof_total 18662
telemt_me_idle_close_by_peer_total 18655
telemt_me_route_drop_no_conn_total 83661
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191614
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18363
telemt_me_refill_failed_total 1407
telemt_me_writer_restored_same_endpoint_total 16718
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1635
telemt_user_connections_total{user="hello"} 194362
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 3213859598 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 78584772221 (73.19 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 25043.3 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25079
telemt_connections_bad_total 4690
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 7840
telemt_upstream_connect_success_total 7766
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 7840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 6537
telemt_me_reconnect_success_total 6514
telemt_me_reader_eof_total 6967
telemt_me_idle_close_by_peer_total 6967
telemt_me_route_drop_no_conn_total 6991
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19590
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6572
telemt_me_writer_restored_same_endpoint_total 6496
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 19590
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 140825016 (134.30 MB)
telemt_user_octets_to_client{user="hello"} 8951712020 (8.34 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 74828.1 (20h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386236
telemt_connections_bad_total 7642
telemt_handshake_timeouts_total 2910
telemt_upstream_connect_attempt_total 15928
telemt_upstream_connect_success_total 15839
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 15928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 1429
telemt_me_reconnect_attempts_total 15723
telemt_me_reconnect_success_total 12095
telemt_me_reader_eof_total 12985
telemt_me_idle_close_by_peer_total 12982
telemt_me_route_drop_no_conn_total 172635
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376634
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 12364
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12088
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 364880
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 6092457040 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 217908344160 (202.94 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 44
```