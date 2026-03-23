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

# Server Metrics 2026-03-23 06:11:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 119130.1 (33h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4272737
telemt_connections_bad_total 405698
telemt_connections_current 1500
telemt_connections_me_current 1500
telemt_handshake_timeouts_total 144599
telemt_upstream_connect_attempt_total 44267
telemt_upstream_connect_success_total 44265
telemt_upstream_connect_attempts_per_request{bucket="1"} 44265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1550
telemt_me_reconnect_success_total 695
telemt_me_reader_eof_total 719
telemt_me_idle_close_by_peer_total 719
telemt_me_route_drop_no_conn_total 3561554
telemt_me_route_drop_channel_closed_total 1374
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3497742
telemt_me_writer_pick_total{mode="p2c",result="full"} 22
telemt_me_endpoint_quarantine_total 849
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 932
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
telemt_me_writers_active_current 44
telemt_desync_total 14499
telemt_desync_full_logged_total 4587
telemt_desync_suppressed_total 9912
telemt_desync_frames_bucket_total{bucket="1_2"} 3748
telemt_desync_frames_bucket_total{bucket="3_10"} 5413
telemt_desync_frames_bucket_total{bucket="gt_10"} 5338
telemt_pool_swap_total 132
telemt_pool_force_close_total 4069
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 777
telemt_me_draining_writers_reap_progress_total 40575
telemt_me_writer_removed_unexpected_total 691
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2916
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37922
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36506
telemt_me_writer_teardown_success_total{mode="normal"} 40838
telemt_me_writer_teardown_noop_total 40588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81426
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 449.215071
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81426
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 777
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 3484895
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 46218779180 (43.04 GB)
telemt_user_octets_to_client{user="hello"} 908516444372 (846.12 GB)
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 132495.9 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4195635
telemt_connections_bad_total 389811
telemt_connections_current 841
telemt_connections_me_current 841
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 110400
telemt_upstream_connect_attempt_total 82410
telemt_upstream_connect_success_total 81419
telemt_upstream_connect_fail_total 879
telemt_upstream_connect_attempts_per_request{bucket="1"} 82298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 879
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11084
telemt_me_reconnect_success_total 3975
telemt_me_reader_eof_total 3944
telemt_me_idle_close_by_peer_total 3943
telemt_me_route_drop_no_conn_total 3681830
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3327203
telemt_me_endpoint_quarantine_total 1084
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1046
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 13725
telemt_desync_full_logged_total 7741
telemt_desync_suppressed_total 5984
telemt_desync_frames_bucket_total{bucket="1_2"} 3115
telemt_desync_frames_bucket_total{bucket="3_10"} 5384
telemt_desync_frames_bucket_total{bucket="gt_10"} 5226
telemt_pool_swap_total 125
telemt_pool_force_close_total 3464
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 272
telemt_me_draining_writers_reap_progress_total 55664
telemt_me_writer_removed_unexpected_total 3866
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7007
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52566
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2955
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52200
telemt_me_writer_teardown_success_total{mode="normal"} 59573
telemt_me_writer_teardown_noop_total 55665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115238
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.018808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115238
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 272
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 3517
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 3341611
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 45010731303 (41.92 GB)
telemt_user_octets_to_client{user="hello"} 846231458721 (788.11 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 207355.8 (57h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16773221
telemt_connections_bad_total 1702994
telemt_connections_current 1815
telemt_connections_me_current 1815
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 413429
telemt_upstream_connect_attempt_total 93007
telemt_upstream_connect_success_total 92896
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 92913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1734
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3277
telemt_me_reconnect_success_total 1703
telemt_me_reader_eof_total 1661
telemt_me_idle_close_by_peer_total 1658
telemt_me_route_drop_no_conn_total 14142115
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13322493
telemt_me_endpoint_quarantine_total 1412
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1571
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
telemt_desync_total 55733
telemt_desync_full_logged_total 17817
telemt_desync_suppressed_total 37916
telemt_desync_frames_bucket_total{bucket="1_2"} 12406
telemt_desync_frames_bucket_total{bucket="3_10"} 21826
telemt_desync_frames_bucket_total{bucket="gt_10"} 21501
telemt_pool_swap_total 225
telemt_pool_force_close_total 7200
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1114
telemt_me_draining_writers_reap_progress_total 71725
telemt_me_writer_removed_unexpected_total 1594
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6016
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66589
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6730
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64525
telemt_me_writer_teardown_success_total{mode="normal"} 72605
telemt_me_writer_teardown_noop_total 71779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144384
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.958512
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144384
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1114
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1474
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13322245
telemt_user_connections_current{user="hello"} 1815
telemt_user_octets_from_client{user="hello"} 201539877973 (187.70 GB)
telemt_user_octets_to_client{user="hello"} 3626400920291 (3.30 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 659
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 207357.1 (57h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12249434
telemt_connections_bad_total 1303102
telemt_connections_current 1212
telemt_connections_me_current 1212
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 355149
telemt_upstream_connect_attempt_total 107452
telemt_upstream_connect_success_total 106037
telemt_upstream_connect_fail_total 901
telemt_upstream_connect_attempts_per_request{bucket="1"} 106938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 901
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4764
telemt_me_reconnect_success_total 2054
telemt_me_reader_eof_total 1909
telemt_me_idle_close_by_peer_total 1909
telemt_me_route_drop_no_conn_total 4627296
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9056682
telemt_me_endpoint_quarantine_total 1419
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1586
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 60
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
telemt_desync_total 39849
telemt_desync_full_logged_total 13473
telemt_desync_suppressed_total 26376
telemt_desync_frames_bucket_total{bucket="1_2"} 9882
telemt_desync_frames_bucket_total{bucket="3_10"} 15297
telemt_desync_frames_bucket_total{bucket="gt_10"} 14670
telemt_pool_swap_total 222
telemt_pool_force_close_total 6553
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 69868
telemt_me_writer_removed_unexpected_total 1939
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6128
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65542
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6038
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63315
telemt_me_writer_teardown_success_total{mode="normal"} 71670
telemt_me_writer_teardown_noop_total 69893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141563
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 105.105873
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141563
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1750
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8994178
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 220913125848 (205.74 GB)
telemt_user_octets_to_client{user="hello"} 4048685830031 (3.68 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 207321.2 (57h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11392263
telemt_connections_bad_total 1048166
telemt_connections_current 1169
telemt_connections_me_current 1169
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 361675
telemt_upstream_connect_attempt_total 91882
telemt_upstream_connect_success_total 90302
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 90507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5931
telemt_me_reconnect_success_total 2515
telemt_me_reader_eof_total 2252
telemt_me_idle_close_by_peer_total 2251
telemt_me_route_drop_no_conn_total 5396170
telemt_me_route_drop_channel_closed_total 387
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8562518
telemt_me_endpoint_quarantine_total 1472
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1553
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
telemt_me_writers_active_current 45
telemt_desync_total 38963
telemt_desync_full_logged_total 12944
telemt_desync_suppressed_total 26019
telemt_desync_frames_bucket_total{bucket="1_2"} 9827
telemt_desync_frames_bucket_total{bucket="3_10"} 14911
telemt_desync_frames_bucket_total{bucket="gt_10"} 14225
telemt_pool_swap_total 218
telemt_pool_force_close_total 6444
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 766
telemt_me_draining_writers_reap_progress_total 70494
telemt_me_writer_removed_unexpected_total 2397
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6876
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65952
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 577
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64050
telemt_me_writer_teardown_success_total{mode="normal"} 72828
telemt_me_writer_teardown_noop_total 70565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143393
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.319856
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143393
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 766
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2184
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 8554253
telemt_user_connections_current{user="hello"} 1169
telemt_user_octets_from_client{user="hello"} 194650064379 (181.28 GB)
telemt_user_octets_to_client{user="hello"} 3548823337333 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 77601.5 (21h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11816428
telemt_connections_bad_total 717311
telemt_connections_current 2203
telemt_connections_me_current 2203
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 330400
telemt_upstream_connect_attempt_total 72299
telemt_upstream_connect_success_total 68558
telemt_upstream_connect_fail_total 2454
telemt_upstream_connect_attempts_per_request{bucket="1"} 71012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2454
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8583
telemt_me_reconnect_success_total 1595
telemt_me_reader_eof_total 1016
telemt_me_idle_close_by_peer_total 1015
telemt_me_route_drop_no_conn_total 25417871
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9750430
telemt_me_endpoint_quarantine_total 621
telemt_me_single_endpoint_outage_enter_total 112
telemt_me_single_endpoint_outage_exit_total 112
telemt_me_single_endpoint_outage_reconnect_attempt_total 214
telemt_me_single_endpoint_outage_reconnect_success_total 57
telemt_me_single_endpoint_quarantine_bypass_total 214
telemt_me_single_endpoint_shadow_rotate_total 625
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
telemt_me_writers_active_current 46
telemt_desync_total 17490
telemt_desync_full_logged_total 4911
telemt_desync_suppressed_total 12579
telemt_desync_frames_bucket_total{bucket="1_2"} 3384
telemt_desync_frames_bucket_total{bucket="3_10"} 7161
telemt_desync_frames_bucket_total{bucket="gt_10"} 6945
telemt_pool_swap_total 80
telemt_pool_force_close_total 2473
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 544
telemt_me_draining_writers_reap_progress_total 25784
telemt_me_writer_removed_unexpected_total 1471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3337
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23863
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2126
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23311
telemt_me_writer_teardown_success_total{mode="normal"} 27200
telemt_me_writer_teardown_noop_total 25803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53003
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.373827
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53003
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 544
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 1018
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 9781602
telemt_user_connections_current{user="hello"} 2204
telemt_user_octets_from_client{user="hello"} 91857045968 (85.55 GB)
telemt_user_octets_to_client{user="hello"} 760841045644 (708.59 GB)
telemt_user_msgs_from_client{user="hello"} 78576
telemt_user_msgs_to_client{user="hello"} 74228
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 320
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 207327.8 (57h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11375564
telemt_connections_bad_total 999329
telemt_connections_current 1555
telemt_connections_me_current 1555
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 258734
telemt_upstream_connect_attempt_total 121001
telemt_upstream_connect_success_total 119705
telemt_upstream_connect_fail_total 1118
telemt_upstream_connect_attempts_per_request{bucket="1"} 120823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1118
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73750
telemt_me_reconnect_success_total 3352
telemt_me_reader_eof_total 3028
telemt_me_idle_close_by_peer_total 3025
telemt_me_route_drop_no_conn_total 5345325
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8955496
telemt_me_endpoint_quarantine_total 1419
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1580
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
telemt_me_writers_active_current 88
telemt_desync_total 47581
telemt_desync_full_logged_total 16373
telemt_desync_suppressed_total 31208
telemt_desync_frames_bucket_total{bucket="1_2"} 9681
telemt_desync_frames_bucket_total{bucket="3_10"} 18237
telemt_desync_frames_bucket_total{bucket="gt_10"} 19663
telemt_pool_swap_total 213
telemt_pool_force_close_total 6123
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 74627
telemt_me_writer_removed_unexpected_total 3045
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70276
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5373
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 750
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68504
telemt_me_writer_teardown_success_total{mode="normal"} 77719
telemt_me_writer_teardown_noop_total 74628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152347
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.396011
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152347
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2820
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8958055
telemt_user_connections_current{user="hello"} 1555
telemt_user_octets_from_client{user="hello"} 199869966945 (186.14 GB)
telemt_user_octets_to_client{user="hello"} 3430607081180 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 682
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 144164.2 (40h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12182839
telemt_connections_bad_total 500774
telemt_connections_current 1113
telemt_connections_me_current 1113
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4906759
telemt_upstream_connect_attempt_total 69864
telemt_upstream_connect_success_total 69366
telemt_upstream_connect_fail_total 485
telemt_upstream_connect_attempts_per_request{bucket="1"} 69851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 485
telemt_me_reconnect_attempts_total 49449
telemt_me_reconnect_success_total 2002
telemt_me_reader_eof_total 1679
telemt_me_idle_close_by_peer_total 1678
telemt_me_route_drop_no_conn_total 4162418
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5854790
telemt_me_endpoint_quarantine_total 994
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32957
telemt_desync_full_logged_total 11299
telemt_desync_suppressed_total 21658
telemt_desync_frames_bucket_total{bucket="1_2"} 6625
telemt_desync_frames_bucket_total{bucket="3_10"} 12978
telemt_desync_frames_bucket_total{bucket="gt_10"} 13354
telemt_pool_swap_total 154
telemt_pool_force_close_total 4314
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 398
telemt_me_draining_writers_reap_progress_total 54538
telemt_me_writer_removed_unexpected_total 1716
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4321
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51991
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3868
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 446
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50224
telemt_me_writer_teardown_success_total{mode="normal"} 56312
telemt_me_writer_teardown_noop_total 54545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110857
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.924086
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110857
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 398
telemt_me_refill_failed_total 2756
telemt_me_writer_restored_same_endpoint_total 1768
telemt_me_writer_restored_fallback_total 31
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4336
telemt_user_connections_total{user="hello"} 5846624
telemt_user_connections_current{user="hello"} 1113
telemt_user_octets_from_client{user="hello"} 122476305196 (114.06 GB)
telemt_user_octets_to_client{user="hello"} 2278218966638 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 125135.0 (34h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1767379
telemt_connections_bad_total 37701
telemt_connections_current 1096
telemt_connections_me_current 1096
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 39275
telemt_upstream_connect_attempt_total 58674
telemt_upstream_connect_success_total 58478
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 58635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 861
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 2524
telemt_me_reconnect_success_total 1030
telemt_me_reader_eof_total 1026
telemt_me_idle_close_by_peer_total 1026
telemt_me_route_drop_no_conn_total 632855
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1569961
telemt_me_endpoint_quarantine_total 1062
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1029
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 9
telemt_desync_total 10617
telemt_desync_full_logged_total 2998
telemt_desync_suppressed_total 7619
telemt_desync_frames_bucket_total{bucket="1_2"} 3366
telemt_desync_frames_bucket_total{bucket="3_10"} 3976
telemt_desync_frames_bucket_total{bucket="gt_10"} 3275
telemt_pool_swap_total 135
telemt_pool_force_close_total 3418
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 50064
telemt_me_writer_removed_unexpected_total 988
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3764
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47336
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3330
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46646
telemt_me_writer_teardown_success_total{mode="normal"} 51100
telemt_me_writer_teardown_noop_total 50068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101168
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.733864
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101168
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 884
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1565480
telemt_user_connections_current{user="hello"} 1096
telemt_user_octets_from_client{user="hello"} 28092734641 (26.16 GB)
telemt_user_octets_to_client{user="hello"} 625157261871 (582.22 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 207332.3 (57h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13665644
telemt_connections_bad_total 1663565
telemt_connections_current 1682
telemt_connections_me_current 1682
telemt_handshake_timeouts_total 400513
telemt_upstream_connect_attempt_total 83685
telemt_upstream_connect_success_total 83316
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 83548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3300
telemt_me_reconnect_success_total 1648
telemt_me_reader_eof_total 1639
telemt_me_idle_close_by_peer_total 1639
telemt_me_route_drop_no_conn_total 4549153
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10298710
telemt_me_endpoint_quarantine_total 1539
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1578
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
telemt_me_writers_active_current 44
telemt_desync_total 43387
telemt_desync_full_logged_total 14121
telemt_desync_suppressed_total 29266
telemt_desync_frames_bucket_total{bucket="1_2"} 10543
telemt_desync_frames_bucket_total{bucket="3_10"} 15967
telemt_desync_frames_bucket_total{bucket="gt_10"} 16877
telemt_pool_swap_total 230
telemt_pool_force_close_total 5993
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 709
telemt_me_draining_writers_reap_progress_total 75760
telemt_me_writer_removed_unexpected_total 1567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5821
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71568
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5819
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69767
telemt_me_writer_teardown_success_total{mode="normal"} 77389
telemt_me_writer_teardown_noop_total 75762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153151
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.150389
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153151
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 709
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1447
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10265032
telemt_user_connections_current{user="hello"} 1682
telemt_user_octets_from_client{user="hello"} 197639078748 (184.07 GB)
telemt_user_octets_to_client{user="hello"} 4580313804832 (4.17 TB)
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 207329.0 (57h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11969754
telemt_connections_bad_total 1401661
telemt_connections_current 1312
telemt_connections_me_current 1312
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 321947
telemt_upstream_connect_attempt_total 111703
telemt_upstream_connect_success_total 110744
telemt_upstream_connect_fail_total 750
telemt_upstream_connect_attempts_per_request{bucket="1"} 111494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 750
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11174
telemt_me_reconnect_success_total 2796
telemt_me_reader_eof_total 2589
telemt_me_idle_close_by_peer_total 2588
telemt_me_seq_mismatch_total 112
telemt_me_route_drop_no_conn_total 5718045
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9218908
telemt_me_endpoint_quarantine_total 1723
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1582
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 60
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
telemt_me_writers_active_current 52
telemt_desync_total 43260
telemt_desync_full_logged_total 13836
telemt_desync_suppressed_total 29424
telemt_desync_frames_bucket_total{bucket="1_2"} 11225
telemt_desync_frames_bucket_total{bucket="3_10"} 15978
telemt_desync_frames_bucket_total{bucket="gt_10"} 16057
telemt_pool_swap_total 220
telemt_pool_force_close_total 5734
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 76257
telemt_me_writer_removed_unexpected_total 2626
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7234
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71753
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70523
telemt_me_writer_teardown_success_total{mode="normal"} 78987
telemt_me_writer_teardown_noop_total 76262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 152505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 154326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 154880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 155199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 155249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 155249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 155249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 155249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 155249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 155249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 155249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 155249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 155249
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.869341
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 155249
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 435
telemt_me_writer_restored_same_endpoint_total 2227
telemt_me_writer_restored_fallback_total 147
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 9223162
telemt_user_connections_current{user="hello"} 1312
telemt_user_octets_from_client{user="hello"} 160295816344 (149.29 GB)
telemt_user_octets_to_client{user="hello"} 3609225634558 (3.28 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 495
telemt_user_unique_ips_recent_window{user="hello"} 178
```