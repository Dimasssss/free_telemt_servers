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

# Server Metrics 2026-03-16 13:00:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 139582.7 (38h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786179
telemt_connections_bad_total 54227
telemt_handshake_timeouts_total 25493
telemt_upstream_connect_attempt_total 32200
telemt_upstream_connect_success_total 32044
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 32200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 39352
telemt_me_reconnect_success_total 25117
telemt_me_reader_eof_total 27082
telemt_me_idle_close_by_peer_total 27082
telemt_me_route_drop_no_conn_total 616114
telemt_me_route_drop_channel_closed_total 98
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 721023
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3438
telemt_desync_full_logged_total 1291
telemt_desync_suppressed_total 2147
telemt_desync_frames_bucket_total{bucket="1_2"} 726
telemt_desync_frames_bucket_total{bucket="3_10"} 1439
telemt_desync_frames_bucket_total{bucket="gt_10"} 1273
telemt_pool_swap_total 125
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25835
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 25082
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 657496
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 13685222004 (12.75 GB)
telemt_user_octets_to_client{user="hello"} 377016625732 (351.12 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 139589.7 (38h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330147
telemt_connections_bad_total 4715
telemt_handshake_timeouts_total 21172
telemt_upstream_connect_attempt_total 37326
telemt_upstream_connect_success_total 37219
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 37326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20273
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 878
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 43574
telemt_me_reconnect_success_total 29627
telemt_me_reader_eof_total 31804
telemt_me_idle_close_by_peer_total 31803
telemt_me_route_drop_no_conn_total 155430
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292200
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 247
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 167
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30488
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 29611
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 861
telemt_user_connections_total{user="hello"} 291878
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 5827909589 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 141648685104 (131.92 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 139582.4 (38h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315691
telemt_connections_bad_total 7188
telemt_handshake_timeouts_total 9011
telemt_upstream_connect_attempt_total 38499
telemt_upstream_connect_success_total 38491
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 38499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38903
telemt_me_reconnect_success_total 31455
telemt_me_reader_eof_total 33762
telemt_me_idle_close_by_peer_total 33761
telemt_me_route_drop_no_conn_total 107052
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257926
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 32010
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31447
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 257521
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 19043073697 (17.74 GB)
telemt_user_octets_to_client{user="hello"} 132750317140 (123.63 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 139581.9 (38h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485066
telemt_connections_bad_total 5598
telemt_handshake_timeouts_total 6133
telemt_upstream_connect_attempt_total 32422
telemt_upstream_connect_success_total 32374
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 32422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 30412
telemt_me_reconnect_success_total 25400
telemt_me_reader_eof_total 27170
telemt_me_idle_close_by_peer_total 27169
telemt_me_route_drop_no_conn_total 161654
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443029
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1569
telemt_desync_full_logged_total 527
telemt_desync_suppressed_total 1042
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 25897
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 25389
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 442849
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 6727568302 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 166714992464 (155.27 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 114653.4 (31h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299108
telemt_connections_bad_total 55000
telemt_handshake_timeouts_total 5251
telemt_upstream_connect_attempt_total 32578
telemt_upstream_connect_success_total 32399
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 32578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 122125
telemt_me_reconnect_success_total 26505
telemt_me_reader_eof_total 28147
telemt_me_idle_close_by_peer_total 28147
telemt_me_route_drop_no_conn_total 89025
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229717
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 721
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 26780
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 26401
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 229318
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 2969976449 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 105129848827 (97.91 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 139581.8 (38h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1017093
telemt_connections_bad_total 78212
telemt_handshake_timeouts_total 12978
telemt_upstream_connect_attempt_total 29537
telemt_upstream_connect_success_total 29383
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 29537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 26064
telemt_me_reconnect_success_total 22412
telemt_me_reader_eof_total 23933
telemt_me_idle_close_by_peer_total 23932
telemt_me_route_drop_no_conn_total 722983
telemt_me_route_drop_channel_closed_total 140
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 986581
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 719
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 494
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 22800
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22385
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 845160
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 17969698452 (16.74 GB)
telemt_user_octets_to_client{user="hello"} 484759046676 (451.47 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 126
```