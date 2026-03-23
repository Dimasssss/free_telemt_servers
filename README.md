# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-23 06:06:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 118824.9 (33h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4246354
telemt_connections_bad_total 403941
telemt_connections_current 1804
telemt_connections_me_current 1804
telemt_handshake_timeouts_total 143555
telemt_upstream_connect_attempt_total 44130
telemt_upstream_connect_success_total 44129
telemt_upstream_connect_attempts_per_request{bucket="1"} 44129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1547
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 3486956
telemt_me_route_drop_channel_closed_total 1366
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3474945
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 842
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 929
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 1
telemt_desync_total 14444
telemt_desync_full_logged_total 4567
telemt_desync_suppressed_total 9877
telemt_desync_frames_bucket_total{bucket="1_2"} 3728
telemt_desync_frames_bucket_total{bucket="3_10"} 5398
telemt_desync_frames_bucket_total{bucket="gt_10"} 5318
telemt_pool_swap_total 131
telemt_pool_force_close_total 4009
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 760
telemt_me_draining_writers_reap_progress_total 40415
telemt_me_writer_removed_unexpected_total 688
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2899
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37804
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36406
telemt_me_writer_teardown_success_total{mode="normal"} 40703
telemt_me_writer_teardown_noop_total 40428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81131
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 442.463260
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81131
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 760
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 621
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 3462216
telemt_user_connections_current{user="hello"} 1804
telemt_user_octets_from_client{user="hello"} 46107258068 (42.94 GB)
telemt_user_octets_to_client{user="hello"} 905780641180 (843.57 GB)
telemt_user_unique_ips_current{user="hello"} 692
telemt_user_unique_ips_recent_window{user="hello"} 414
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 132191.3 (36h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4189106
telemt_connections_bad_total 388772
telemt_connections_current 844
telemt_connections_me_current 844
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 109969
telemt_upstream_connect_attempt_total 82248
telemt_upstream_connect_success_total 81264
telemt_upstream_connect_fail_total 872
telemt_upstream_connect_attempts_per_request{bucket="1"} 82136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 872
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11020
telemt_me_reconnect_success_total 3967
telemt_me_reader_eof_total 3937
telemt_me_idle_close_by_peer_total 3936
telemt_me_route_drop_no_conn_total 3680229
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3322588
telemt_me_endpoint_quarantine_total 1074
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1039
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 13688
telemt_desync_full_logged_total 7723
telemt_desync_suppressed_total 5965
telemt_desync_frames_bucket_total{bucket="1_2"} 3109
telemt_desync_frames_bucket_total{bucket="3_10"} 5363
telemt_desync_frames_bucket_total{bucket="gt_10"} 5216
telemt_pool_swap_total 124
telemt_pool_force_close_total 3464
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 272
telemt_me_draining_writers_reap_progress_total 55549
telemt_me_writer_removed_unexpected_total 3859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52459
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2955
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52085
telemt_me_writer_teardown_success_total{mode="normal"} 59451
telemt_me_writer_teardown_noop_total 55550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115001
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.013206
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115001
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 272
telemt_me_refill_failed_total 279
telemt_me_writer_restored_same_endpoint_total 3513
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 3336996
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 44930405003 (41.84 GB)
telemt_user_octets_to_client{user="hello"} 844542584813 (786.54 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 207051.1 (57h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16757798
telemt_connections_bad_total 1701249
telemt_connections_current 2010
telemt_connections_me_current 2010
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 412561
telemt_upstream_connect_attempt_total 92849
telemt_upstream_connect_success_total 92738
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 92755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1734
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3275
telemt_me_reconnect_success_total 1702
telemt_me_reader_eof_total 1660
telemt_me_idle_close_by_peer_total 1657
telemt_me_route_drop_no_conn_total 14138567
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13310002
telemt_me_endpoint_quarantine_total 1405
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1567
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 1
telemt_desync_total 55645
telemt_desync_full_logged_total 17787
telemt_desync_suppressed_total 37858
telemt_desync_frames_bucket_total{bucket="1_2"} 12393
telemt_desync_frames_bucket_total{bucket="3_10"} 21794
telemt_desync_frames_bucket_total{bucket="gt_10"} 21458
telemt_pool_swap_total 224
telemt_pool_force_close_total 7175
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1108
telemt_me_draining_writers_reap_progress_total 71568
telemt_me_writer_removed_unexpected_total 1593
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5991
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6705
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64393
telemt_me_writer_teardown_success_total{mode="normal"} 72447
telemt_me_writer_teardown_noop_total 71622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144069
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.355509
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144069
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1108
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1473
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13309779
telemt_user_connections_current{user="hello"} 2010
telemt_user_octets_from_client{user="hello"} 201372087245 (187.54 GB)
telemt_user_octets_to_client{user="hello"} 3621751776459 (3.29 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 771
telemt_user_unique_ips_recent_window{user="hello"} 287
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 207052.6 (57h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12239191
telemt_connections_bad_total 1301512
telemt_connections_current 1379
telemt_connections_me_current 1379
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 354911
telemt_upstream_connect_attempt_total 107295
telemt_upstream_connect_success_total 105880
telemt_upstream_connect_fail_total 901
telemt_upstream_connect_attempts_per_request{bucket="1"} 106781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45884
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 901
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4748
telemt_me_reconnect_success_total 2045
telemt_me_reader_eof_total 1904
telemt_me_idle_close_by_peer_total 1904
telemt_me_route_drop_no_conn_total 4625170
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9049248
telemt_me_endpoint_quarantine_total 1411
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1583
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 5
telemt_desync_total 39813
telemt_desync_full_logged_total 13462
telemt_desync_suppressed_total 26351
telemt_desync_frames_bucket_total{bucket="1_2"} 9867
telemt_desync_frames_bucket_total{bucket="3_10"} 15291
telemt_desync_frames_bucket_total{bucket="gt_10"} 14655
telemt_pool_swap_total 221
telemt_pool_force_close_total 6523
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 69712
telemt_me_writer_removed_unexpected_total 1934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6100
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65409
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6010
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 513
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63189
telemt_me_writer_teardown_success_total{mode="normal"} 71509
telemt_me_writer_teardown_noop_total 69737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141246
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.730134
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141246
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1745
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8986768
telemt_user_connections_current{user="hello"} 1379
telemt_user_octets_from_client{user="hello"} 220847880420 (205.68 GB)
telemt_user_octets_to_client{user="hello"} 4046232224199 (3.68 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 207016.5 (57h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11383863
telemt_connections_bad_total 1047087
telemt_connections_current 1202
telemt_connections_me_current 1202
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 361454
telemt_upstream_connect_attempt_total 91713
telemt_upstream_connect_success_total 90134
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 90339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5921
telemt_me_reconnect_success_total 2500
telemt_me_reader_eof_total 2242
telemt_me_idle_close_by_peer_total 2241
telemt_me_route_drop_no_conn_total 5393579
telemt_me_route_drop_channel_closed_total 386
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8555730
telemt_me_endpoint_quarantine_total 1462
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1547
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 38950
telemt_desync_full_logged_total 12935
telemt_desync_suppressed_total 26015
telemt_desync_frames_bucket_total{bucket="1_2"} 9824
telemt_desync_frames_bucket_total{bucket="3_10"} 14907
telemt_desync_frames_bucket_total{bucket="gt_10"} 14219
telemt_pool_swap_total 217
telemt_pool_force_close_total 6412
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 764
telemt_me_draining_writers_reap_progress_total 70343
telemt_me_writer_removed_unexpected_total 2387
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6842
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65825
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5838
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 574
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63931
telemt_me_writer_teardown_success_total{mode="normal"} 72667
telemt_me_writer_teardown_noop_total 70414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143081
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.293830
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143081
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 764
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2176
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8547480
telemt_user_connections_current{user="hello"} 1202
telemt_user_octets_from_client{user="hello"} 194578773519 (181.22 GB)
telemt_user_octets_to_client{user="hello"} 3546274092125 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 77296.6 (21h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11791073
telemt_connections_bad_total 715831
telemt_connections_current 2343
telemt_connections_me_current 2343
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 327559
telemt_upstream_connect_attempt_total 68355
telemt_upstream_connect_success_total 64750
telemt_upstream_connect_fail_total 2323
telemt_upstream_connect_attempts_per_request{bucket="1"} 67073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2323
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8530
telemt_me_reconnect_success_total 1587
telemt_me_reader_eof_total 1007
telemt_me_idle_close_by_peer_total 1006
telemt_me_route_drop_no_conn_total 25412060
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9735596
telemt_me_endpoint_quarantine_total 613
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 619
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 17465
telemt_desync_full_logged_total 4906
telemt_desync_suppressed_total 12559
telemt_desync_frames_bucket_total{bucket="1_2"} 3378
telemt_desync_frames_bucket_total{bucket="3_10"} 7154
telemt_desync_frames_bucket_total{bucket="gt_10"} 6933
telemt_pool_swap_total 79
telemt_pool_force_close_total 2473
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 534
telemt_me_draining_writers_reap_progress_total 25638
telemt_me_writer_removed_unexpected_total 1463
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3294
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23760
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2126
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23165
telemt_me_writer_teardown_success_total{mode="normal"} 27054
telemt_me_writer_teardown_noop_total 25657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52711
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.191736
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52711
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 534
telemt_me_refill_failed_total 353
telemt_me_writer_restored_same_endpoint_total 1015
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 9763106
telemt_user_connections_current{user="hello"} 2343
telemt_user_octets_from_client{user="hello"} 91723493535 (85.42 GB)
telemt_user_octets_to_client{user="hello"} 756814883609 (704.84 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 789
telemt_user_unique_ips_recent_window{user="hello"} 319
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 207023.2 (57h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11364731
telemt_connections_bad_total 998691
telemt_connections_current 1560
telemt_connections_me_current 1560
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 258275
telemt_upstream_connect_attempt_total 120763
telemt_upstream_connect_success_total 119479
telemt_upstream_connect_fail_total 1107
telemt_upstream_connect_attempts_per_request{bucket="1"} 120586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1107
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73708
telemt_me_reconnect_success_total 3310
telemt_me_reader_eof_total 2985
telemt_me_idle_close_by_peer_total 2982
telemt_me_route_drop_no_conn_total 5341166
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8946628
telemt_me_endpoint_quarantine_total 1418
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1574
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 47550
telemt_desync_full_logged_total 16362
telemt_desync_suppressed_total 31188
telemt_desync_frames_bucket_total{bucket="1_2"} 9671
telemt_desync_frames_bucket_total{bucket="3_10"} 18229
telemt_desync_frames_bucket_total{bucket="gt_10"} 19650
telemt_pool_swap_total 213
telemt_pool_force_close_total 6123
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 74490
telemt_me_writer_removed_unexpected_total 3002
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7394
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70145
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5373
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 750
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68367
telemt_me_writer_teardown_success_total{mode="normal"} 77539
telemt_me_writer_teardown_noop_total 74491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.394018
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2778
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8949189
telemt_user_connections_current{user="hello"} 1560
telemt_user_octets_from_client{user="hello"} 199767893545 (186.05 GB)
telemt_user_octets_to_client{user="hello"} 3425993340708 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 143859.5 (39h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12166104
telemt_connections_bad_total 498523
telemt_connections_current 1211
telemt_connections_me_current 1211
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4903999
telemt_upstream_connect_attempt_total 69691
telemt_upstream_connect_success_total 69199
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 69678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_reconnect_attempts_total 49416
telemt_me_reconnect_success_total 1983
telemt_me_reader_eof_total 1669
telemt_me_idle_close_by_peer_total 1668
telemt_me_route_drop_no_conn_total 4159492
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5847421
telemt_me_endpoint_quarantine_total 988
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1111
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32886
telemt_desync_full_logged_total 11270
telemt_desync_suppressed_total 21616
telemt_desync_frames_bucket_total{bucket="1_2"} 6610
telemt_desync_frames_bucket_total{bucket="3_10"} 12949
telemt_desync_frames_bucket_total{bucket="gt_10"} 13327
telemt_pool_swap_total 153
telemt_pool_force_close_total 4312
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 54407
telemt_me_writer_removed_unexpected_total 1706
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4299
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51872
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3868
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50095
telemt_me_writer_teardown_success_total{mode="normal"} 56171
telemt_me_writer_teardown_noop_total 54414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.922657
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 2755
telemt_me_writer_restored_same_endpoint_total 1752
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5839278
telemt_user_connections_current{user="hello"} 1211
telemt_user_octets_from_client{user="hello"} 122349272472 (113.95 GB)
telemt_user_octets_to_client{user="hello"} 2275704023682 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 124830.3 (34h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1750599
telemt_connections_bad_total 37695
telemt_connections_current 1030
telemt_connections_me_current 1030
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 38815
telemt_upstream_connect_attempt_total 58574
telemt_upstream_connect_success_total 58379
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 58536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 859
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 2524
telemt_me_reconnect_success_total 1030
telemt_me_reader_eof_total 1026
telemt_me_idle_close_by_peer_total 1026
telemt_me_route_drop_no_conn_total 603769
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1554605
telemt_me_endpoint_quarantine_total 1062
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1028
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 10593
telemt_desync_full_logged_total 2992
telemt_desync_suppressed_total 7601
telemt_desync_frames_bucket_total{bucket="1_2"} 3357
telemt_desync_frames_bucket_total{bucket="3_10"} 3963
telemt_desync_frames_bucket_total{bucket="gt_10"} 3273
telemt_pool_swap_total 135
telemt_pool_force_close_total 3418
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 49977
telemt_me_writer_removed_unexpected_total 988
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3763
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47250
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3330
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46559
telemt_me_writer_teardown_success_total{mode="normal"} 51013
telemt_me_writer_teardown_noop_total 49981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.731529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 884
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1550123
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 28009540957 (26.09 GB)
telemt_user_octets_to_client{user="hello"} 624170929819 (581.30 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 207027.7 (57h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13653655
telemt_connections_bad_total 1661062
telemt_connections_current 1630
telemt_connections_me_current 1630
telemt_handshake_timeouts_total 400355
telemt_upstream_connect_attempt_total 83514
telemt_upstream_connect_success_total 83145
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 83377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3294
telemt_me_reconnect_success_total 1642
telemt_me_reader_eof_total 1633
telemt_me_idle_close_by_peer_total 1633
telemt_me_route_drop_no_conn_total 4546721
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10289537
telemt_me_endpoint_quarantine_total 1534
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1573
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 2
telemt_desync_total 43291
telemt_desync_full_logged_total 14108
telemt_desync_suppressed_total 29183
telemt_desync_frames_bucket_total{bucket="1_2"} 10529
telemt_desync_frames_bucket_total{bucket="3_10"} 15904
telemt_desync_frames_bucket_total{bucket="gt_10"} 16858
telemt_pool_swap_total 229
telemt_pool_force_close_total 5970
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 75592
telemt_me_writer_removed_unexpected_total 1561
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5796
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71419
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69622
telemt_me_writer_teardown_success_total{mode="normal"} 77215
telemt_me_writer_teardown_noop_total 75594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152809
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.132366
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152809
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10255910
telemt_user_connections_current{user="hello"} 1630
telemt_user_octets_from_client{user="hello"} 197514509088 (183.95 GB)
telemt_user_octets_to_client{user="hello"} 4575438591732 (4.16 TB)
telemt_user_unique_ips_current{user="hello"} 609
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 207024.4 (57h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11955932
telemt_connections_bad_total 1396658
telemt_connections_current 1513
telemt_connections_me_current 1513
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 321716
telemt_upstream_connect_attempt_total 111494
telemt_upstream_connect_success_total 110540
telemt_upstream_connect_fail_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 111285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 745
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11149
telemt_me_reconnect_success_total 2778
telemt_me_reader_eof_total 2580
telemt_me_idle_close_by_peer_total 2579
telemt_me_seq_mismatch_total 112
telemt_me_route_drop_no_conn_total 5715217
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9210719
telemt_me_endpoint_quarantine_total 1714
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1577
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 43213
telemt_desync_full_logged_total 13823
telemt_desync_suppressed_total 29390
telemt_desync_frames_bucket_total{bucket="1_2"} 11210
telemt_desync_frames_bucket_total{bucket="3_10"} 15964
telemt_desync_frames_bucket_total{bucket="gt_10"} 16039
telemt_pool_swap_total 219
telemt_pool_force_close_total 5710
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 76080
telemt_me_writer_removed_unexpected_total 2618
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70370
telemt_me_writer_teardown_success_total{mode="normal"} 78801
telemt_me_writer_teardown_noop_total 76085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 152142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 154517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 154836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 154886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 154886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 154886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 154886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 154886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 154886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 154886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 154886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 154886
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.862514
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 154886
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 435
telemt_me_writer_restored_same_endpoint_total 2213
telemt_me_writer_restored_fallback_total 147
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 9214997
telemt_user_connections_current{user="hello"} 1513
telemt_user_octets_from_client{user="hello"} 160156583716 (149.16 GB)
telemt_user_octets_to_client{user="hello"} 3605611748578 (3.28 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 213
```