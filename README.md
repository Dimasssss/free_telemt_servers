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

# Server Metrics 2026-03-16 11:13:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 133137.7 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718209
telemt_connections_bad_total 53844
telemt_handshake_timeouts_total 23036
telemt_upstream_connect_attempt_total 30850
telemt_upstream_connect_success_total 30702
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 30850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 38331
telemt_me_reconnect_success_total 24106
telemt_me_reader_eof_total 26025
telemt_me_idle_close_by_peer_total 26025
telemt_me_route_drop_no_conn_total 597493
telemt_me_route_drop_channel_closed_total 90
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661937
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3047
telemt_desync_full_logged_total 1168
telemt_desync_suppressed_total 1879
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 1186
telemt_desync_frames_bucket_total{bucket="gt_10"} 1195
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24809
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24071
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 703
telemt_user_connections_total{user="hello"} 598470
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 11525245988 (10.73 GB)
telemt_user_octets_to_client{user="hello"} 353652322084 (329.36 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 133144.4 (36h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287959
telemt_connections_bad_total 3804
telemt_handshake_timeouts_total 17263
telemt_upstream_connect_attempt_total 35682
telemt_upstream_connect_success_total 35575
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 35682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 823
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1679
telemt_me_reconnect_attempts_total 38707
telemt_me_reconnect_success_total 28356
telemt_me_reader_eof_total 30400
telemt_me_idle_close_by_peer_total 30399
telemt_me_route_drop_no_conn_total 139894
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255661
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 29082
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28340
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 255376
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 5322097965 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 131556544904 (122.52 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 133137.2 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285032
telemt_connections_bad_total 5850
telemt_handshake_timeouts_total 7474
telemt_upstream_connect_attempt_total 37078
telemt_upstream_connect_success_total 37070
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37825
telemt_me_reconnect_success_total 30395
telemt_me_reader_eof_total 32629
telemt_me_idle_close_by_peer_total 32628
telemt_me_route_drop_no_conn_total 97905
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232317
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 30933
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30387
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 231958
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 18769903297 (17.48 GB)
telemt_user_octets_to_client{user="hello"} 126206604680 (117.54 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 133136.7 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424100
telemt_connections_bad_total 1439
telemt_handshake_timeouts_total 3931
telemt_upstream_connect_attempt_total 30734
telemt_upstream_connect_success_total 30690
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 30734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 29072
telemt_me_reconnect_success_total 24070
telemt_me_reader_eof_total 25788
telemt_me_idle_close_by_peer_total 25787
telemt_me_route_drop_no_conn_total 145870
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393537
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1476
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 983
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 632
telemt_desync_frames_bucket_total{bucket="gt_10"} 550
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 24550
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24059
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 393405
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 6293330718 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 152108167448 (141.66 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 108207.8 (30h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264107
telemt_connections_bad_total 45044
telemt_handshake_timeouts_total 4370
telemt_upstream_connect_attempt_total 30950
telemt_upstream_connect_success_total 30783
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 30950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 120651
telemt_me_reconnect_success_total 25210
telemt_me_reader_eof_total 26773
telemt_me_idle_close_by_peer_total 26773
telemt_me_route_drop_no_conn_total 80948
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206524
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 689
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 523
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 25455
telemt_me_refill_failed_total 3062
telemt_me_writer_restored_same_endpoint_total 25106
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 206145
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 2634853013 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 91868424027 (85.56 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 133136.1 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 932571
telemt_connections_bad_total 73494
telemt_handshake_timeouts_total 10963
telemt_upstream_connect_attempt_total 28049
telemt_upstream_connect_success_total 27901
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 28048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 23892
telemt_me_reconnect_success_total 21278
telemt_me_reader_eof_total 22719
telemt_me_idle_close_by_peer_total 22718
telemt_me_route_drop_no_conn_total 691419
telemt_me_route_drop_channel_closed_total 126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 915926
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 523
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 21614
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21251
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 774539
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 16196037456 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 450296016612 (419.37 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 105
```