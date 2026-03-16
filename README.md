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

# Server Metrics 2026-03-16 10:27:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 130374.0 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 649356
telemt_connections_bad_total 14666
telemt_handshake_timeouts_total 22508
telemt_upstream_connect_attempt_total 30502
telemt_upstream_connect_success_total 30356
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 30502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 33995
telemt_me_reconnect_success_total 23899
telemt_me_reader_eof_total 25688
telemt_me_idle_close_by_peer_total 25688
telemt_me_route_drop_no_conn_total 590797
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633736
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2942
telemt_desync_full_logged_total 1135
telemt_desync_suppressed_total 1807
telemt_desync_frames_bucket_total{bucket="1_2"} 648
telemt_desync_frames_bucket_total{bucket="3_10"} 1126
telemt_desync_frames_bucket_total{bucket="gt_10"} 1168
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24472
telemt_me_refill_failed_total 311
telemt_me_writer_restored_same_endpoint_total 23864
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 573
telemt_user_connections_total{user="hello"} 570289
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 11005038248 (10.25 GB)
telemt_user_octets_to_client{user="hello"} 346150273180 (322.38 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 130381.6 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268216
telemt_connections_bad_total 3798
telemt_handshake_timeouts_total 15694
telemt_upstream_connect_attempt_total 34866
telemt_upstream_connect_success_total 34791
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 34866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 716
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 38242
telemt_me_reconnect_success_total 27917
telemt_me_reader_eof_total 29937
telemt_me_idle_close_by_peer_total 29936
telemt_me_route_drop_no_conn_total 126959
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239481
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 28633
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 27901
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 716
telemt_user_connections_total{user="hello"} 239014
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 5090249865 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 127082278460 (118.35 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 130374.2 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273724
telemt_connections_bad_total 5769
telemt_handshake_timeouts_total 6577
telemt_upstream_connect_attempt_total 36315
telemt_upstream_connect_success_total 36307
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 36315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37197
telemt_me_reconnect_success_total 29773
telemt_me_reader_eof_total 31986
telemt_me_idle_close_by_peer_total 31985
telemt_me_route_drop_no_conn_total 94814
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222345
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 111
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 30297
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29765
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 222033
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 17736611625 (16.52 GB)
telemt_user_octets_to_client{user="hello"} 121319481724 (112.99 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 130373.7 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399718
telemt_connections_bad_total 1415
telemt_handshake_timeouts_total 3722
telemt_upstream_connect_attempt_total 30048
telemt_upstream_connect_success_total 30007
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 30048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 28524
telemt_me_reconnect_success_total 23534
telemt_me_reader_eof_total 25234
telemt_me_idle_close_by_peer_total 25233
telemt_me_route_drop_no_conn_total 139190
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370289
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1357
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 902
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 573
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 24002
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 23523
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 370160
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 6095362834 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 146041050080 (136.01 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 105445.0 (29h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251038
telemt_connections_bad_total 41726
telemt_handshake_timeouts_total 4317
telemt_upstream_connect_attempt_total 30009
telemt_upstream_connect_success_total 29844
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 30009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 118924
telemt_me_reconnect_success_total 24415
telemt_me_reader_eof_total 25933
telemt_me_idle_close_by_peer_total 25933
telemt_me_route_drop_no_conn_total 77398
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197875
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 663
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 508
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 267
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24622
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24311
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 197489
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 2547558157 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 88634974587 (82.55 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 130373.1 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 897283
telemt_connections_bad_total 73018
telemt_handshake_timeouts_total 10406
telemt_upstream_connect_attempt_total 27328
telemt_upstream_connect_success_total 27185
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 27328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 23309
telemt_me_reconnect_success_total 20701
telemt_me_reader_eof_total 22117
telemt_me_idle_close_by_peer_total 22117
telemt_me_route_drop_no_conn_total 678482
telemt_me_route_drop_channel_closed_total 123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 883911
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 436
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 311
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 21029
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20674
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 742533
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 15718780388 (14.64 GB)
telemt_user_octets_to_client{user="hello"} 440116113828 (409.89 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 96
```