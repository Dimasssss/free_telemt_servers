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

# Server Metrics 2026-03-22 06:25:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 33568.0 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639740
telemt_connections_bad_total 39761
telemt_connections_current 1302
telemt_connections_me_current 1302
telemt_handshake_timeouts_total 31612
telemt_upstream_connect_attempt_total 13774
telemt_upstream_connect_success_total 13773
telemt_upstream_connect_attempts_per_request{bucket="1"} 13773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 368
telemt_me_reconnect_success_total 217
telemt_me_reader_eof_total 213
telemt_me_idle_close_by_peer_total 213
telemt_me_route_drop_no_conn_total 232394
telemt_me_route_drop_channel_closed_total 75
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530405
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_shadow_rotate_total 278
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 4484
telemt_desync_full_logged_total 1246
telemt_desync_suppressed_total 3238
telemt_desync_frames_bucket_total{bucket="1_2"} 1480
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1321
telemt_pool_swap_total 37
telemt_pool_force_close_total 988
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 12455
telemt_me_writer_removed_unexpected_total 210
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 861
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11791
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 978
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11467
telemt_me_writer_teardown_success_total{mode="normal"} 12652
telemt_me_writer_teardown_noop_total 12456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25108
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.340501
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25108
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 529300
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 7241285748 (6.74 GB)
telemt_user_octets_to_client{user="hello"} 184241540708 (171.59 GB)
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 46934.0 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1099056
telemt_connections_bad_total 100581
telemt_connections_current 1858
telemt_connections_me_current 1858
telemt_handshake_timeouts_total 36119
telemt_upstream_connect_attempt_total 24902
telemt_upstream_connect_success_total 24555
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 24870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1862
telemt_me_reconnect_success_total 707
telemt_me_reader_eof_total 630
telemt_me_idle_close_by_peer_total 630
telemt_me_route_drop_no_conn_total 408335
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 838621
telemt_me_endpoint_quarantine_total 420
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 376
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_me_writers_active_current 92
telemt_me_writers_warm_current 32
telemt_desync_total 3531
telemt_desync_full_logged_total 2057
telemt_desync_suppressed_total 1474
telemt_desync_frames_bucket_total{bucket="1_2"} 744
telemt_desync_frames_bucket_total{bucket="3_10"} 1360
telemt_desync_frames_bucket_total{bucket="gt_10"} 1427
telemt_pool_swap_total 49
telemt_pool_force_close_total 1287
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 19373
telemt_me_writer_removed_unexpected_total 604
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1675
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18316
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18086
telemt_me_writer_teardown_success_total{mode="normal"} 19991
telemt_me_writer_teardown_noop_total 19373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39364
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.476010
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39364
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 840294
telemt_user_connections_current{user="hello"} 1858
telemt_user_octets_from_client{user="hello"} 13705186259 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 313023752258 (291.53 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 121793.8 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8598498
telemt_connections_bad_total 773942
telemt_connections_current 3288
telemt_connections_me_current 3288
telemt_handshake_timeouts_total 275407
telemt_upstream_connect_attempt_total 45215
telemt_upstream_connect_success_total 45137
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1732
telemt_me_reconnect_success_total 898
telemt_me_reader_eof_total 903
telemt_me_idle_close_by_peer_total 903
telemt_me_route_drop_no_conn_total 4741985
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6841602
telemt_me_endpoint_quarantine_total 776
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 915
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_me_writers_active_current 47
telemt_desync_total 29225
telemt_desync_full_logged_total 9702
telemt_desync_suppressed_total 19523
telemt_desync_frames_bucket_total{bucket="1_2"} 6324
telemt_desync_frames_bucket_total{bucket="3_10"} 11414
telemt_desync_frames_bucket_total{bucket="gt_10"} 11487
telemt_pool_swap_total 132
telemt_pool_force_close_total 4360
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 41273
telemt_me_writer_removed_unexpected_total 868
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3431
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38217
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 257
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36913
telemt_me_writer_teardown_success_total{mode="normal"} 41648
telemt_me_writer_teardown_noop_total 41317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 172.748802
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 803
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 6832689
telemt_user_connections_current{user="hello"} 3288
telemt_user_octets_from_client{user="hello"} 115813083140 (107.86 GB)
telemt_user_octets_to_client{user="hello"} 2330976387744 (2.12 TB)
telemt_user_unique_ips_current{user="hello"} 1293
telemt_user_unique_ips_recent_window{user="hello"} 539
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 121795.5 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7090329
telemt_connections_bad_total 629012
telemt_connections_current 3613
telemt_connections_me_current 3613
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 235954
telemt_upstream_connect_attempt_total 49160
telemt_upstream_connect_success_total 48755
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 48963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2067
telemt_me_reconnect_success_total 943
telemt_me_reader_eof_total 923
telemt_me_idle_close_by_peer_total 923
telemt_me_route_drop_no_conn_total 2405152
telemt_me_route_drop_channel_closed_total 294
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5272658
telemt_me_endpoint_quarantine_total 771
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 938
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 24403
telemt_desync_full_logged_total 8385
telemt_desync_suppressed_total 16018
telemt_desync_frames_bucket_total{bucket="1_2"} 5834
telemt_desync_frames_bucket_total{bucket="3_10"} 9467
telemt_desync_frames_bucket_total{bucket="gt_10"} 9102
telemt_pool_swap_total 133
telemt_pool_force_close_total 3961
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 402
telemt_me_draining_writers_reap_progress_total 39704
telemt_me_writer_removed_unexpected_total 900
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3271
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37262
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3739
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 222
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35743
telemt_me_writer_teardown_success_total{mode="normal"} 40533
telemt_me_writer_teardown_noop_total 39710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.052581
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 402
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5193925
telemt_user_connections_current{user="hello"} 3613
telemt_user_octets_from_client{user="hello"} 149381267173 (139.12 GB)
telemt_user_octets_to_client{user="hello"} 2504670035111 (2.28 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1329
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 121760.5 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6885831
telemt_connections_bad_total 575679
telemt_connections_current 2989
telemt_connections_me_current 2989
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 231890
telemt_upstream_connect_attempt_total 55625
telemt_upstream_connect_success_total 55026
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2585
telemt_me_reconnect_success_total 1116
telemt_me_reader_eof_total 1039
telemt_me_idle_close_by_peer_total 1039
telemt_me_route_drop_no_conn_total 2485536
telemt_me_route_drop_channel_closed_total 155
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5117039
telemt_me_endpoint_quarantine_total 871
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 906
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
telemt_me_writers_active_current 47
telemt_desync_total 24292
telemt_desync_full_logged_total 8228
telemt_desync_suppressed_total 16064
telemt_desync_frames_bucket_total{bucket="1_2"} 5896
telemt_desync_frames_bucket_total{bucket="3_10"} 9329
telemt_desync_frames_bucket_total{bucket="gt_10"} 9067
telemt_pool_swap_total 131
telemt_pool_force_close_total 3832
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 40667
telemt_me_writer_removed_unexpected_total 1030
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3582
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 250
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36835
telemt_me_writer_teardown_success_total{mode="normal"} 41709
telemt_me_writer_teardown_noop_total 40679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82388
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.066188
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82388
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 963
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 5111187
telemt_user_connections_current{user="hello"} 2989
telemt_user_octets_from_client{user="hello"} 139644640143 (130.05 GB)
telemt_user_octets_to_client{user="hello"} 2325378727563 (2.11 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1213
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 121798.5 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21991548
telemt_connections_bad_total 1864182
telemt_connections_current 4738
telemt_connections_me_current 4738
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 663341
telemt_upstream_connect_attempt_total 225277
telemt_upstream_connect_success_total 206119
telemt_upstream_connect_fail_total 17228
telemt_upstream_connect_attempts_per_request{bucket="1"} 223347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17228
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66341
telemt_me_reconnect_success_total 2593
telemt_me_reader_eof_total 1629
telemt_me_idle_close_by_peer_total 1627
telemt_me_route_drop_no_conn_total 41583449
telemt_me_route_drop_channel_closed_total 133
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17677338
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 957
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 34219
telemt_desync_full_logged_total 10278
telemt_desync_suppressed_total 23941
telemt_desync_frames_bucket_total{bucket="1_2"} 7548
telemt_desync_frames_bucket_total{bucket="3_10"} 15138
telemt_desync_frames_bucket_total{bucket="gt_10"} 11533
telemt_pool_swap_total 126
telemt_pool_force_close_total 4019
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 909
telemt_me_draining_writers_reap_progress_total 38209
telemt_me_writer_removed_unexpected_total 2404
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5188
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3448
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34190
telemt_me_writer_teardown_success_total{mode="normal"} 40363
telemt_me_writer_teardown_noop_total 38239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78602
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 227.683101
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78602
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 909
telemt_me_refill_failed_total 3862
telemt_me_writer_restored_same_endpoint_total 1762
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 17829945
telemt_user_connections_current{user="hello"} 4738
telemt_user_octets_from_client{user="hello"} 264559096217 (246.39 GB)
telemt_user_octets_to_client{user="hello"} 1366858068259 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 454370
telemt_user_msgs_to_client{user="hello"} 903931
telemt_user_unique_ips_current{user="hello"} 1742
telemt_user_unique_ips_recent_window{user="hello"} 904
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 121766.1 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6612609
telemt_connections_bad_total 618239
telemt_connections_current 2585
telemt_connections_me_current 2585
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 137691
telemt_upstream_connect_attempt_total 64252
telemt_upstream_connect_success_total 63513
telemt_upstream_connect_fail_total 633
telemt_upstream_connect_attempts_per_request{bucket="1"} 64146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 633
telemt_me_reconnect_attempts_total 69988
telemt_me_reconnect_success_total 1908
telemt_me_reader_eof_total 1684
telemt_me_idle_close_by_peer_total 1683
telemt_me_route_drop_no_conn_total 2534748
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5161336
telemt_me_endpoint_quarantine_total 822
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 925
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 25699
telemt_desync_full_logged_total 8984
telemt_desync_suppressed_total 16715
telemt_desync_frames_bucket_total{bucket="1_2"} 5076
telemt_desync_frames_bucket_total{bucket="3_10"} 9879
telemt_desync_frames_bucket_total{bucket="gt_10"} 10744
telemt_pool_swap_total 127
telemt_pool_force_close_total 3642
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 42896
telemt_me_writer_removed_unexpected_total 1717
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4308
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40340
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 408
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39254
telemt_me_writer_teardown_success_total{mode="normal"} 44648
telemt_me_writer_teardown_noop_total 42897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87545
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.900490
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87545
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1593
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5153039
telemt_user_connections_current{user="hello"} 2585
telemt_user_octets_from_client{user="hello"} 132084232892 (123.01 GB)
telemt_user_octets_to_client{user="hello"} 2152544454102 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1043
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 58602.0 (16h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4714260
telemt_connections_bad_total 197277
telemt_connections_current 3545
telemt_connections_me_current 3545
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1853183
telemt_upstream_connect_attempt_total 33012
telemt_upstream_connect_success_total 32788
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 33005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_reconnect_attempts_total 46176
telemt_me_reconnect_success_total 1054
telemt_me_reader_eof_total 745
telemt_me_idle_close_by_peer_total 745
telemt_me_route_drop_no_conn_total 1170154
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2348047
telemt_me_endpoint_quarantine_total 414
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 449
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_writers_warm_current 38
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12556
telemt_desync_full_logged_total 4331
telemt_desync_suppressed_total 8225
telemt_desync_frames_bucket_total{bucket="1_2"} 2414
telemt_desync_frames_bucket_total{bucket="3_10"} 4806
telemt_desync_frames_bucket_total{bucket="gt_10"} 5336
telemt_pool_swap_total 63
telemt_pool_force_close_total 1848
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 162
telemt_me_draining_writers_reap_progress_total 21470
telemt_me_writer_removed_unexpected_total 815
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1820
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20495
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1635
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19622
telemt_me_writer_teardown_success_total{mode="normal"} 22315
telemt_me_writer_teardown_noop_total 21472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43787
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.760865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43787
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 162
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 939
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2350157
telemt_user_connections_current{user="hello"} 3545
telemt_user_octets_from_client{user="hello"} 61341529920 (57.13 GB)
telemt_user_octets_to_client{user="hello"} 1043803343838 (972.12 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1545
telemt_user_unique_ips_recent_window{user="hello"} 462
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 39572.7 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291382
telemt_connections_bad_total 2043
telemt_connections_current 558
telemt_connections_me_current 558
telemt_handshake_timeouts_total 7027
telemt_upstream_connect_attempt_total 19010
telemt_upstream_connect_success_total 18964
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 19006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 490
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 84540
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262123
telemt_me_endpoint_quarantine_total 370
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 341
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 1299
telemt_desync_full_logged_total 364
telemt_desync_suppressed_total 935
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 499
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 43
telemt_pool_force_close_total 962
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 17222
telemt_me_writer_removed_unexpected_total 250
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16387
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 960
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16260
telemt_me_writer_teardown_success_total{mode="normal"} 17483
telemt_me_writer_teardown_noop_total 17222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.356494
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 226
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 261717
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 4366366904 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 154271298876 (143.68 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 121771.0 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8022879
telemt_connections_bad_total 811182
telemt_connections_current 3530
telemt_connections_me_current 3530
telemt_handshake_timeouts_total 226371
telemt_upstream_connect_attempt_total 47917
telemt_upstream_connect_success_total 47744
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24061
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 1762
telemt_me_reconnect_success_total 944
telemt_me_reader_eof_total 928
telemt_me_idle_close_by_peer_total 928
telemt_me_route_drop_no_conn_total 2269271
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5990114
telemt_me_endpoint_quarantine_total 872
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 934
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 23584
telemt_desync_full_logged_total 7758
telemt_desync_suppressed_total 15826
telemt_desync_frames_bucket_total{bucket="1_2"} 5886
telemt_desync_frames_bucket_total{bucket="3_10"} 8603
telemt_desync_frames_bucket_total{bucket="gt_10"} 9095
telemt_pool_swap_total 135
telemt_pool_force_close_total 3602
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 424
telemt_me_draining_writers_reap_progress_total 43270
telemt_me_writer_removed_unexpected_total 891
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3390
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40798
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3511
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39668
telemt_me_writer_teardown_success_total{mode="normal"} 44188
telemt_me_writer_teardown_noop_total 43272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87460
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.216213
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87460
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 424
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 840
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 5964323
telemt_user_connections_current{user="hello"} 3530
telemt_user_octets_from_client{user="hello"} 116833762596 (108.81 GB)
telemt_user_octets_to_client{user="hello"} 2800245837356 (2.55 TB)
telemt_user_unique_ips_current{user="hello"} 1323
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 121767.4 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7003954
telemt_connections_bad_total 703688
telemt_connections_current 3765
telemt_connections_me_current 3765
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 187711
telemt_upstream_connect_attempt_total 63713
telemt_upstream_connect_success_total 63225
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 63650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_reconnect_attempts_total 5864
telemt_me_reconnect_success_total 1312
telemt_me_reader_eof_total 1179
telemt_me_idle_close_by_peer_total 1179
telemt_me_seq_mismatch_total 58
telemt_me_route_drop_no_conn_total 2328176
telemt_me_route_drop_channel_closed_total 196
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5354012
telemt_me_endpoint_quarantine_total 963
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 934
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 22469
telemt_desync_full_logged_total 7478
telemt_desync_suppressed_total 14991
telemt_desync_frames_bucket_total{bucket="1_2"} 5631
telemt_desync_frames_bucket_total{bucket="3_10"} 8208
telemt_desync_frames_bucket_total{bucket="gt_10"} 8630
telemt_pool_swap_total 133
telemt_pool_force_close_total 3547
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 426
telemt_me_draining_writers_reap_progress_total 41751
telemt_me_writer_removed_unexpected_total 1191
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39058
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3322
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38204
telemt_me_writer_teardown_success_total{mode="normal"} 43003
telemt_me_writer_teardown_noop_total 41755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84758
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.066867
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84758
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 426
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 1021
telemt_me_writer_restored_fallback_total 77
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5356246
telemt_user_connections_current{user="hello"} 3765
telemt_user_octets_from_client{user="hello"} 99874497557 (93.02 GB)
telemt_user_octets_to_client{user="hello"} 2326761246756 (2.12 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1382
telemt_user_unique_ips_recent_window{user="hello"} 561
```