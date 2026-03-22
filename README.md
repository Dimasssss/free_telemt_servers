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

# Server Metrics 2026-03-22 16:44:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 70705.5 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2515429
telemt_connections_bad_total 134977
telemt_connections_current 1745
telemt_connections_me_current 1745
telemt_handshake_timeouts_total 88757
telemt_upstream_connect_attempt_total 26078
telemt_upstream_connect_success_total 26077
telemt_upstream_connect_attempts_per_request{bucket="1"} 26077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1039
telemt_me_reconnect_success_total 445
telemt_me_reader_eof_total 448
telemt_me_idle_close_by_peer_total 448
telemt_me_route_drop_no_conn_total 2035624
telemt_me_route_drop_channel_closed_total 849
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2143800
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 554
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
telemt_me_writers_active_current 43
telemt_desync_total 10205
telemt_desync_full_logged_total 3211
telemt_desync_suppressed_total 6994
telemt_desync_frames_bucket_total{bucket="1_2"} 2725
telemt_desync_frames_bucket_total{bucket="3_10"} 3817
telemt_desync_frames_bucket_total{bucket="gt_10"} 3663
telemt_pool_swap_total 78
telemt_pool_force_close_total 2425
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 23840
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1736
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22315
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2374
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21415
telemt_me_writer_teardown_success_total{mode="normal"} 24051
telemt_me_writer_teardown_noop_total 23846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47897
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 225.958464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47897
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2140305
telemt_user_connections_current{user="hello"} 1745
telemt_user_octets_from_client{user="hello"} 32254041740 (30.04 GB)
telemt_user_octets_to_client{user="hello"} 569547086860 (530.43 GB)
telemt_user_unique_ips_current{user="hello"} 629
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 84071.9 (23h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3620868
telemt_connections_bad_total 329207
telemt_connections_current 695
telemt_connections_me_current 695
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 90137
telemt_upstream_connect_attempt_total 52693
telemt_upstream_connect_success_total 52053
telemt_upstream_connect_fail_total 568
telemt_upstream_connect_attempts_per_request{bucket="1"} 52621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 568
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6105
telemt_me_reconnect_success_total 2211
telemt_me_reader_eof_total 2150
telemt_me_idle_close_by_peer_total 2150
telemt_me_route_drop_no_conn_total 3537633
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2870201
telemt_me_endpoint_quarantine_total 672
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 648
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 42
telemt_desync_total 11239
telemt_desync_full_logged_total 6270
telemt_desync_suppressed_total 4969
telemt_desync_frames_bucket_total{bucket="1_2"} 2612
telemt_desync_frames_bucket_total{bucket="3_10"} 4410
telemt_desync_frames_bucket_total{bucket="gt_10"} 4217
telemt_pool_swap_total 79
telemt_pool_force_close_total 2375
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 199
telemt_me_draining_writers_reap_progress_total 33580
telemt_me_writer_removed_unexpected_total 2103
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31669
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2017
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 358
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31205
telemt_me_writer_teardown_success_total{mode="normal"} 35691
telemt_me_writer_teardown_noop_total 33580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69271
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.017312
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69271
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 199
telemt_me_refill_failed_total 153
telemt_me_writer_restored_same_endpoint_total 1918
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 2881457
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 36077452095 (33.60 GB)
telemt_user_octets_to_client{user="hello"} 647421979678 (602.96 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 158931.9 (44h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15374456
telemt_connections_bad_total 1437543
telemt_connections_current 2264
telemt_connections_me_current 2264
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 374529
telemt_upstream_connect_attempt_total 71723
telemt_upstream_connect_success_total 71627
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 71644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2673
telemt_me_reconnect_success_total 1364
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1301
telemt_me_route_drop_no_conn_total 13819555
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12283187
telemt_me_endpoint_quarantine_total 1002
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1185
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 50071
telemt_desync_full_logged_total 15725
telemt_desync_suppressed_total 34346
telemt_desync_frames_bucket_total{bucket="1_2"} 11192
telemt_desync_frames_bucket_total{bucket="3_10"} 19563
telemt_desync_frames_bucket_total{bucket="gt_10"} 19316
telemt_pool_swap_total 171
telemt_pool_force_close_total 5823
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 941
telemt_me_draining_writers_reap_progress_total 52287
telemt_me_writer_removed_unexpected_total 1257
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48281
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46464
telemt_me_writer_teardown_success_total{mode="normal"} 52835
telemt_me_writer_teardown_noop_total 52337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105172
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 301.785728
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105172
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 941
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1171
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 12284317
telemt_user_connections_current{user="hello"} 2264
telemt_user_octets_from_client{user="hello"} 175229683989 (163.20 GB)
telemt_user_octets_to_client{user="hello"} 3182381320971 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 886
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 158933.3 (44h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11093227
telemt_connections_bad_total 1078407
telemt_connections_current 1599
telemt_connections_me_current 1599
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 329499
telemt_upstream_connect_attempt_total 83913
telemt_upstream_connect_success_total 82756
telemt_upstream_connect_fail_total 833
telemt_upstream_connect_attempts_per_request{bucket="1"} 83589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3695
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 833
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3947
telemt_me_reconnect_success_total 1611
telemt_me_reader_eof_total 1483
telemt_me_idle_close_by_peer_total 1483
telemt_me_route_drop_no_conn_total 4369019
telemt_me_route_drop_channel_closed_total 479
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8273732
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1202
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36777
telemt_desync_full_logged_total 12366
telemt_desync_suppressed_total 24411
telemt_desync_frames_bucket_total{bucket="1_2"} 9033
telemt_desync_frames_bucket_total{bucket="3_10"} 14168
telemt_desync_frames_bucket_total{bucket="gt_10"} 13576
telemt_pool_swap_total 169
telemt_pool_force_close_total 5241
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 50559
telemt_me_writer_removed_unexpected_total 1511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4663
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47268
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45318
telemt_me_writer_teardown_success_total{mode="normal"} 51931
telemt_me_writer_teardown_noop_total 50577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102508
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.278003
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102508
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1373
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8212359
telemt_user_connections_current{user="hello"} 1599
telemt_user_octets_from_client{user="hello"} 205423894921 (191.32 GB)
telemt_user_octets_to_client{user="hello"} 3701942091194 (3.37 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 609
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 158898.7 (44h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10489050
telemt_connections_bad_total 903846
telemt_connections_current 1287
telemt_connections_me_current 1287
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 335444
telemt_upstream_connect_attempt_total 69086
telemt_upstream_connect_success_total 68119
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 68301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2082
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4725
telemt_me_reconnect_success_total 1907
telemt_me_reader_eof_total 1659
telemt_me_idle_close_by_peer_total 1658
telemt_me_route_drop_no_conn_total 5141860
telemt_me_route_drop_channel_closed_total 360
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7915174
telemt_me_endpoint_quarantine_total 1090
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1170
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_me_writers_active_current 44
telemt_desync_total 36219
telemt_desync_full_logged_total 12000
telemt_desync_suppressed_total 24219
telemt_desync_frames_bucket_total{bucket="1_2"} 9166
telemt_desync_frames_bucket_total{bucket="3_10"} 13841
telemt_desync_frames_bucket_total{bucket="gt_10"} 13212
telemt_pool_swap_total 166
telemt_pool_force_close_total 5191
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 50917
telemt_me_writer_removed_unexpected_total 1799
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5107
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47522
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45726
telemt_me_writer_teardown_success_total{mode="normal"} 52629
telemt_me_writer_teardown_noop_total 50988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.784020
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 1646
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 7908096
telemt_user_connections_current{user="hello"} 1287
telemt_user_octets_from_client{user="hello"} 182526701541 (169.99 GB)
telemt_user_octets_to_client{user="hello"} 3288047837549 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 29177.4 (8h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10210744
telemt_connections_bad_total 623573
telemt_connections_current 2235
telemt_connections_me_current 2235
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 192271
telemt_upstream_connect_attempt_total 36181
telemt_upstream_connect_success_total 34379
telemt_upstream_connect_fail_total 1256
telemt_upstream_connect_attempts_per_request{bucket="1"} 35635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5306
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1256
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5899
telemt_me_reconnect_success_total 720
telemt_me_reader_eof_total 463
telemt_me_idle_close_by_peer_total 463
telemt_me_route_drop_no_conn_total 24954525
telemt_me_route_drop_channel_closed_total 49
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8499014
telemt_me_endpoint_quarantine_total 179
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 230
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 13287
telemt_desync_full_logged_total 3437
telemt_desync_suppressed_total 9850
telemt_desync_frames_bucket_total{bucket="1_2"} 2366
telemt_desync_frames_bucket_total{bucket="3_10"} 5404
telemt_desync_frames_bucket_total{bucket="gt_10"} 5517
telemt_pool_swap_total 28
telemt_pool_force_close_total 1097
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 8043
telemt_me_writer_removed_unexpected_total 623
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1310
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7321
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 817
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6946
telemt_me_writer_teardown_success_total{mode="normal"} 8631
telemt_me_writer_teardown_noop_total 8048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16679
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.439681
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16679
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 495
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8517062
telemt_user_connections_current{user="hello"} 2235
telemt_user_octets_from_client{user="hello"} 64704727022 (60.26 GB)
telemt_user_octets_to_client{user="hello"} 319208213256 (297.29 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 806
telemt_user_unique_ips_recent_window{user="hello"} 333
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 158904.0 (44h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10282593
telemt_connections_bad_total 863127
telemt_connections_current 1801
telemt_connections_me_current 1801
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 228542
telemt_upstream_connect_attempt_total 97855
telemt_upstream_connect_success_total 96844
telemt_upstream_connect_fail_total 863
telemt_upstream_connect_attempts_per_request{bucket="1"} 97707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1308
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 863
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72045
telemt_me_reconnect_success_total 2627
telemt_me_reader_eof_total 2330
telemt_me_idle_close_by_peer_total 2328
telemt_me_route_drop_no_conn_total 5072518
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8108723
telemt_me_endpoint_quarantine_total 1073
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1185
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 42340
telemt_desync_full_logged_total 14445
telemt_desync_suppressed_total 27895
telemt_desync_frames_bucket_total{bucket="1_2"} 8593
telemt_desync_frames_bucket_total{bucket="3_10"} 16372
telemt_desync_frames_bucket_total{bucket="gt_10"} 17375
telemt_pool_swap_total 162
telemt_pool_force_close_total 4820
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 604
telemt_me_draining_writers_reap_progress_total 54052
telemt_me_writer_removed_unexpected_total 2373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5776
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50670
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4135
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49232
telemt_me_writer_teardown_success_total{mode="normal"} 56446
telemt_me_writer_teardown_noop_total 54053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110499
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.482347
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110499
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 604
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2199
telemt_me_writer_restored_fallback_total 45
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8112622
telemt_user_connections_current{user="hello"} 1801
telemt_user_octets_from_client{user="hello"} 183546922137 (170.94 GB)
telemt_user_octets_to_client{user="hello"} 3055501843360 (2.78 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 700
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 95740.1 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10711843
telemt_connections_bad_total 402790
telemt_connections_current 1475
telemt_connections_me_current 1475
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4494440
telemt_upstream_connect_attempt_total 46077
telemt_upstream_connect_success_total 45741
telemt_upstream_connect_fail_total 327
telemt_upstream_connect_attempts_per_request{bucket="1"} 46068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 327
telemt_me_reconnect_attempts_total 48148
telemt_me_reconnect_success_total 1524
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1189
telemt_me_route_drop_no_conn_total 3926253
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5134680
telemt_me_endpoint_quarantine_total 623
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 722
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 28183
telemt_desync_full_logged_total 9525
telemt_desync_suppressed_total 18658
telemt_desync_frames_bucket_total{bucket="1_2"} 5690
telemt_desync_frames_bucket_total{bucket="3_10"} 11115
telemt_desync_frames_bucket_total{bucket="gt_10"} 11378
telemt_pool_swap_total 101
telemt_pool_force_close_total 3106
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 318
telemt_me_draining_writers_reap_progress_total 33012
telemt_me_writer_removed_unexpected_total 1253
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2969
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31326
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2687
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29906
telemt_me_writer_teardown_success_total{mode="normal"} 34295
telemt_me_writer_teardown_noop_total 33019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67314
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.919390
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67314
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 318
telemt_me_refill_failed_total 2710
telemt_me_writer_restored_same_endpoint_total 1355
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5128154
telemt_user_connections_current{user="hello"} 1475
telemt_user_octets_from_client{user="hello"} 110334717488 (102.76 GB)
telemt_user_octets_to_client{user="hello"} 1937964392922 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 76711.0 (21h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1044578
telemt_connections_bad_total 15582
telemt_connections_current 1191
telemt_connections_me_current 1191
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20059
telemt_upstream_connect_attempt_total 37573
telemt_upstream_connect_success_total 37472
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 37553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_reconnect_attempts_total 1726
telemt_me_reconnect_success_total 718
telemt_me_reader_eof_total 693
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 365512
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 930013
telemt_me_endpoint_quarantine_total 656
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 633
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_me_writers_active_current 44
telemt_desync_total 5264
telemt_desync_full_logged_total 1612
telemt_desync_suppressed_total 3652
telemt_desync_frames_bucket_total{bucket="1_2"} 1236
telemt_desync_frames_bucket_total{bucket="3_10"} 2078
telemt_desync_frames_bucket_total{bucket="gt_10"} 1950
telemt_pool_swap_total 82
telemt_pool_force_close_total 2085
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 31142
telemt_me_writer_removed_unexpected_total 669
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2412
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29425
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2003
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29057
telemt_me_writer_teardown_success_total{mode="normal"} 31837
telemt_me_writer_teardown_noop_total 31145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62982
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.766055
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62982
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 611
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 926536
telemt_user_connections_current{user="hello"} 1191
telemt_user_octets_from_client{user="hello"} 16612935357 (15.47 GB)
telemt_user_octets_to_client{user="hello"} 406520839875 (378.60 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 383
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 158908.5 (44h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12556237
telemt_connections_bad_total 1455091
telemt_connections_current 1808
telemt_connections_me_current 1808
telemt_handshake_timeouts_total 347010
telemt_upstream_connect_attempt_total 59690
telemt_upstream_connect_success_total 59443
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 59625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_reconnect_attempts_total 2345
telemt_me_reconnect_success_total 1241
telemt_me_reader_eof_total 1205
telemt_me_idle_close_by_peer_total 1205
telemt_me_route_drop_no_conn_total 4191635
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9496779
telemt_me_endpoint_quarantine_total 1070
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1188
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 48
telemt_desync_total 38985
telemt_desync_full_logged_total 12726
telemt_desync_suppressed_total 26259
telemt_desync_frames_bucket_total{bucket="1_2"} 9269
telemt_desync_frames_bucket_total{bucket="3_10"} 14448
telemt_desync_frames_bucket_total{bucket="gt_10"} 15268
telemt_pool_swap_total 176
telemt_pool_force_close_total 4862
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 621
telemt_me_draining_writers_reap_progress_total 53745
telemt_me_writer_removed_unexpected_total 1158
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4413
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50523
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4688
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48883
telemt_me_writer_teardown_success_total{mode="normal"} 54936
telemt_me_writer_teardown_noop_total 53747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108683
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.262829
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108683
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 621
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 9465966
telemt_user_connections_current{user="hello"} 1808
telemt_user_octets_from_client{user="hello"} 185902796364 (173.14 GB)
telemt_user_octets_to_client{user="hello"} 4181394348808 (3.80 TB)
telemt_user_unique_ips_current{user="hello"} 672
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 158905.1 (44h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10885464
telemt_connections_bad_total 1215715
telemt_connections_current 1622
telemt_connections_me_current 1622
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 280894
telemt_upstream_connect_attempt_total 85508
telemt_upstream_connect_success_total 84841
telemt_upstream_connect_fail_total 561
telemt_upstream_connect_attempts_per_request{bucket="1"} 85402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 561
telemt_me_reconnect_attempts_total 9008
telemt_me_reconnect_success_total 2074
telemt_me_reader_eof_total 1933
telemt_me_idle_close_by_peer_total 1933
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5434008
telemt_me_route_drop_channel_closed_total 348
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8418571
telemt_me_endpoint_quarantine_total 1211
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1190
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 38396
telemt_desync_full_logged_total 12403
telemt_desync_suppressed_total 25993
telemt_desync_frames_bucket_total{bucket="1_2"} 9543
telemt_desync_frames_bucket_total{bucket="3_10"} 14305
telemt_desync_frames_bucket_total{bucket="gt_10"} 14548
telemt_pool_swap_total 168
telemt_pool_force_close_total 4699
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 608
telemt_me_draining_writers_reap_progress_total 53237
telemt_me_writer_removed_unexpected_total 1959
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5510
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49755
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4260
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48538
telemt_me_writer_teardown_success_total{mode="normal"} 55265
telemt_me_writer_teardown_noop_total 53242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108507
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.605976
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108507
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 608
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 1681
telemt_me_writer_restored_fallback_total 100
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 8424526
telemt_user_connections_current{user="hello"} 1622
telemt_user_octets_from_client{user="hello"} 148261652925 (138.08 GB)
telemt_user_octets_to_client{user="hello"} 3219298404315 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 247
```