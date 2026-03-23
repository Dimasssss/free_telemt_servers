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

# Server Metrics 2026-03-23 02:27:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 105652.2 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3626197
telemt_connections_bad_total 339277
telemt_connections_current 942
telemt_connections_me_current 942
telemt_handshake_timeouts_total 115228
telemt_upstream_connect_attempt_total 39390
telemt_upstream_connect_success_total 39389
telemt_upstream_connect_attempts_per_request{bucket="1"} 39389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1415
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 635
telemt_me_route_drop_no_conn_total 2998916
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2973520
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 825
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12821
telemt_desync_full_logged_total 4050
telemt_desync_suppressed_total 8771
telemt_desync_frames_bucket_total{bucket="1_2"} 3416
telemt_desync_frames_bucket_total{bucket="3_10"} 4676
telemt_desync_frames_bucket_total{bucket="gt_10"} 4729
telemt_pool_swap_total 117
telemt_pool_force_close_total 3584
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 36084
telemt_me_writer_removed_unexpected_total 612
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2572
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33773
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3528
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32500
telemt_me_writer_teardown_success_total{mode="normal"} 36345
telemt_me_writer_teardown_noop_total 36095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72440
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.261345
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72440
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 553
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2962479
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 42354101208 (39.45 GB)
telemt_user_octets_to_client{user="hello"} 809826025276 (754.21 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 119018.6 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4024137
telemt_connections_bad_total 372117
telemt_connections_current 193
telemt_connections_me_current 193
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101237
telemt_upstream_connect_attempt_total 74065
telemt_upstream_connect_success_total 73156
telemt_upstream_connect_fail_total 802
telemt_upstream_connect_attempts_per_request{bucket="1"} 73958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 802
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10392
telemt_me_reconnect_success_total 3700
telemt_me_reader_eof_total 3683
telemt_me_idle_close_by_peer_total 3683
telemt_me_route_drop_no_conn_total 3643955
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3196518
telemt_me_endpoint_quarantine_total 965
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 935
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
telemt_me_writers_active_current 43
telemt_desync_total 13035
telemt_desync_full_logged_total 7319
telemt_desync_suppressed_total 5716
telemt_desync_frames_bucket_total{bucket="1_2"} 2959
telemt_desync_frames_bucket_total{bucket="3_10"} 5117
telemt_desync_frames_bucket_total{bucket="gt_10"} 4959
telemt_pool_swap_total 112
telemt_pool_force_close_total 3158
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 49291
telemt_me_writer_removed_unexpected_total 3612
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6411
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46526
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46133
telemt_me_writer_teardown_success_total{mode="normal"} 52937
telemt_me_writer_teardown_noop_total 49292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102229
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.655709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102229
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 3282
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 3209881
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 43274495182 (40.30 GB)
telemt_user_octets_to_client{user="hello"} 796751394442 (742.03 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 193878.4 (53h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16399026
telemt_connections_bad_total 1662582
telemt_connections_current 988
telemt_connections_me_current 988
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 398411
telemt_upstream_connect_attempt_total 87199
telemt_upstream_connect_success_total 87093
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 87110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3038
telemt_me_reconnect_success_total 1614
telemt_me_reader_eof_total 1562
telemt_me_idle_close_by_peer_total 1560
telemt_me_route_drop_no_conn_total 14054278
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13020572
telemt_me_endpoint_quarantine_total 1301
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1462
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_active_current 43
telemt_desync_total 54028
telemt_desync_full_logged_total 17192
telemt_desync_suppressed_total 36836
telemt_desync_frames_bucket_total{bucket="1_2"} 12058
telemt_desync_frames_bucket_total{bucket="3_10"} 21099
telemt_desync_frames_bucket_total{bucket="gt_10"} 20871
telemt_pool_swap_total 210
telemt_pool_force_close_total 6834
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1067
telemt_me_draining_writers_reap_progress_total 66436
telemt_me_writer_removed_unexpected_total 1502
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5619
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61598
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59602
telemt_me_writer_teardown_success_total{mode="normal"} 67217
telemt_me_writer_teardown_noop_total 66489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133706
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.912082
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133706
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1067
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1397
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13020561
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 197528561217 (183.96 GB)
telemt_user_octets_to_client{user="hello"} 3506138657211 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 193879.8 (53h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11946560
telemt_connections_bad_total 1249653
telemt_connections_current 680
telemt_connections_me_current 680
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345116
telemt_upstream_connect_attempt_total 101560
telemt_upstream_connect_success_total 100227
telemt_upstream_connect_fail_total 879
telemt_upstream_connect_attempts_per_request{bucket="1"} 101106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 879
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4470
telemt_me_reconnect_success_total 1921
telemt_me_reader_eof_total 1787
telemt_me_idle_close_by_peer_total 1787
telemt_me_route_drop_no_conn_total 4562918
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8854772
telemt_me_endpoint_quarantine_total 1316
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1483
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39041
telemt_desync_full_logged_total 13146
telemt_desync_suppressed_total 25895
telemt_desync_frames_bucket_total{bucket="1_2"} 9673
telemt_desync_frames_bucket_total{bucket="3_10"} 14994
telemt_desync_frames_bucket_total{bucket="gt_10"} 14374
telemt_pool_swap_total 207
telemt_pool_force_close_total 6186
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 64629
telemt_me_writer_removed_unexpected_total 1814
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5720
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60582
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5674
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58443
telemt_me_writer_teardown_success_total{mode="normal"} 66302
telemt_me_writer_teardown_noop_total 64654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130956
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.526449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130956
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1644
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8792496
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 218120827932 (203.14 GB)
telemt_user_octets_to_client{user="hello"} 3974606423635 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 193843.8 (53h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11098247
telemt_connections_bad_total 984224
telemt_connections_current 460
telemt_connections_me_current 460
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345979
telemt_upstream_connect_attempt_total 85853
telemt_upstream_connect_success_total 84292
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 84497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5788
telemt_me_reconnect_success_total 2410
telemt_me_reader_eof_total 2155
telemt_me_idle_close_by_peer_total 2154
telemt_me_route_drop_no_conn_total 5343189
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8385803
telemt_me_endpoint_quarantine_total 1365
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1441
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 38255
telemt_desync_full_logged_total 12678
telemt_desync_suppressed_total 25577
telemt_desync_frames_bucket_total{bucket="1_2"} 9666
telemt_desync_frames_bucket_total{bucket="3_10"} 14646
telemt_desync_frames_bucket_total{bucket="gt_10"} 13943
telemt_pool_swap_total 203
telemt_pool_force_close_total 6082
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 746
telemt_me_draining_writers_reap_progress_total 65010
telemt_me_writer_removed_unexpected_total 2303
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6465
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60782
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5511
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58928
telemt_me_writer_teardown_success_total{mode="normal"} 67247
telemt_me_writer_teardown_noop_total 65081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.850291
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 746
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2097
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 8377725
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 193003524123 (179.75 GB)
telemt_user_octets_to_client{user="hello"} 3480719861589 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 64124.2 (17h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11322066
telemt_connections_bad_total 670000
telemt_connections_current 1043
telemt_connections_me_current 1043
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 283238
telemt_upstream_connect_attempt_total 60243
telemt_upstream_connect_success_total 57108
telemt_upstream_connect_fail_total 2052
telemt_upstream_connect_attempts_per_request{bucket="1"} 59160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2052
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7855
telemt_me_reconnect_success_total 1323
telemt_me_reader_eof_total 855
telemt_me_idle_close_by_peer_total 854
telemt_me_route_drop_no_conn_total 25301199
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9388991
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 513
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 86
telemt_desync_total 16484
telemt_desync_full_logged_total 4521
telemt_desync_suppressed_total 11963
telemt_desync_frames_bucket_total{bucket="1_2"} 3140
telemt_desync_frames_bucket_total{bucket="3_10"} 6722
telemt_desync_frames_bucket_total{bucket="gt_10"} 6622
telemt_pool_swap_total 66
telemt_pool_force_close_total 2110
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 491
telemt_me_draining_writers_reap_progress_total 20567
telemt_me_writer_removed_unexpected_total 1211
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2726
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18996
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18457
telemt_me_writer_teardown_success_total{mode="normal"} 21722
telemt_me_writer_teardown_noop_total 20586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42308
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.970642
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42308
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 491
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 868
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 9414843
telemt_user_connections_current{user="hello"} 1043
telemt_user_octets_from_client{user="hello"} 87699130334 (81.68 GB)
telemt_user_octets_to_client{user="hello"} 626501865646 (583.48 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 193850.5 (53h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11056627
telemt_connections_bad_total 965768
telemt_connections_current 663
telemt_connections_me_current 663
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 243950
telemt_upstream_connect_attempt_total 114699
telemt_upstream_connect_success_total 113520
telemt_upstream_connect_fail_total 1005
telemt_upstream_connect_attempts_per_request{bucket="1"} 114525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1005
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73144
telemt_me_reconnect_success_total 3143
telemt_me_reader_eof_total 2840
telemt_me_idle_close_by_peer_total 2838
telemt_me_route_drop_no_conn_total 5270303
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8712873
telemt_me_endpoint_quarantine_total 1317
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1469
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 46427
telemt_desync_full_logged_total 15927
telemt_desync_suppressed_total 30500
telemt_desync_frames_bucket_total{bucket="1_2"} 9440
telemt_desync_frames_bucket_total{bucket="3_10"} 17772
telemt_desync_frames_bucket_total{bucket="gt_10"} 19215
telemt_pool_swap_total 199
telemt_pool_force_close_total 5792
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 668
telemt_me_draining_writers_reap_progress_total 69056
telemt_me_writer_removed_unexpected_total 2860
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7016
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64944
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5043
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63264
telemt_me_writer_teardown_success_total{mode="normal"} 71960
telemt_me_writer_teardown_noop_total 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.302396
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 668
telemt_me_refill_failed_total 4308
telemt_me_writer_restored_same_endpoint_total 2648
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 8715802
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 196238175013 (182.76 GB)
telemt_user_octets_to_client{user="hello"} 3330655266636 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 130686.8 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11759371
telemt_connections_bad_total 483068
telemt_connections_current 372
telemt_connections_me_current 372
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4768801
telemt_upstream_connect_attempt_total 63320
telemt_upstream_connect_success_total 62859
telemt_upstream_connect_fail_total 449
telemt_upstream_connect_attempts_per_request{bucket="1"} 63308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 449
telemt_me_reconnect_attempts_total 49103
telemt_me_reconnect_success_total 1869
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1545
telemt_me_route_drop_no_conn_total 4099686
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5651977
telemt_me_endpoint_quarantine_total 898
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1005
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31814
telemt_desync_full_logged_total 10866
telemt_desync_suppressed_total 20948
telemt_desync_frames_bucket_total{bucket="1_2"} 6346
telemt_desync_frames_bucket_total{bucket="3_10"} 12559
telemt_desync_frames_bucket_total{bucket="gt_10"} 12909
telemt_pool_swap_total 139
telemt_pool_force_close_total 4000
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 48641
telemt_me_writer_removed_unexpected_total 1591
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3926
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46355
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3559
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44641
telemt_me_writer_teardown_success_total{mode="normal"} 50281
telemt_me_writer_teardown_noop_total 48648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98929
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.724285
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98929
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5644099
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 120165729596 (111.91 GB)
telemt_user_octets_to_client{user="hello"} 2192349183718 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 111657.7 (31h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1553626
telemt_connections_bad_total 36860
telemt_connections_current 464
telemt_connections_me_current 464
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31895
telemt_upstream_connect_attempt_total 52846
telemt_upstream_connect_success_total 52681
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 52817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2316
telemt_me_reconnect_success_total 946
telemt_me_reader_eof_total 935
telemt_me_idle_close_by_peer_total 935
telemt_me_route_drop_no_conn_total 524373
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1381370
telemt_me_endpoint_quarantine_total 939
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 923
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 18
telemt_desync_total 9540
telemt_desync_full_logged_total 2726
telemt_desync_suppressed_total 6814
telemt_desync_frames_bucket_total{bucket="1_2"} 2864
telemt_desync_frames_bucket_total{bucket="3_10"} 3613
telemt_desync_frames_bucket_total{bucket="gt_10"} 3063
telemt_pool_swap_total 120
telemt_pool_force_close_total 3039
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 44835
telemt_me_writer_removed_unexpected_total 901
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3403
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42374
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2951
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41796
telemt_me_writer_teardown_success_total{mode="normal"} 45777
telemt_me_writer_teardown_noop_total 44839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90616
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.402410
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90616
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 807
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1377154
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 26284731141 (24.48 GB)
telemt_user_octets_to_client{user="hello"} 583674596859 (543.59 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 193855.1 (53h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13380406
telemt_connections_bad_total 1617859
telemt_connections_current 760
telemt_connections_me_current 760
telemt_handshake_timeouts_total 390671
telemt_upstream_connect_attempt_total 77174
telemt_upstream_connect_success_total 76820
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 77038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38811
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3055
telemt_me_reconnect_success_total 1533
telemt_me_reader_eof_total 1518
telemt_me_idle_close_by_peer_total 1518
telemt_me_route_drop_no_conn_total 4488395
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10078058
telemt_me_endpoint_quarantine_total 1414
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 43
telemt_desync_total 42272
telemt_desync_full_logged_total 13804
telemt_desync_suppressed_total 28468
telemt_desync_frames_bucket_total{bucket="1_2"} 10280
telemt_desync_frames_bucket_total{bucket="3_10"} 15528
telemt_desync_frames_bucket_total{bucket="gt_10"} 16464
telemt_pool_swap_total 215
telemt_pool_force_close_total 5677
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 69812
telemt_me_writer_removed_unexpected_total 1453
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5503
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64135
telemt_me_writer_teardown_success_total{mode="normal"} 71320
telemt_me_writer_teardown_noop_total 69814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.827029
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1346
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10044732
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 195018126252 (181.62 GB)
telemt_user_octets_to_client{user="hello"} 4463787938820 (4.06 TB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 193851.7 (53h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11688696
telemt_connections_bad_total 1366397
telemt_connections_current 535
telemt_connections_me_current 535
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312763
telemt_upstream_connect_attempt_total 104815
telemt_upstream_connect_success_total 103911
telemt_upstream_connect_fail_total 696
telemt_upstream_connect_attempts_per_request{bucket="1"} 104607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 696
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10673
telemt_me_reconnect_success_total 2637
telemt_me_reader_eof_total 2447
telemt_me_idle_close_by_peer_total 2446
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5655718
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8992583
telemt_me_endpoint_quarantine_total 1589
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1473
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41951
telemt_desync_full_logged_total 13510
telemt_desync_suppressed_total 28441
telemt_desync_frames_bucket_total{bucket="1_2"} 10848
telemt_desync_frames_bucket_total{bucket="3_10"} 15430
telemt_desync_frames_bucket_total{bucket="gt_10"} 15673
telemt_pool_swap_total 205
telemt_pool_force_close_total 5443
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 671
telemt_me_draining_writers_reap_progress_total 69996
telemt_me_writer_removed_unexpected_total 2488
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6824
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65750
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64553
telemt_me_writer_teardown_success_total{mode="normal"} 72574
telemt_me_writer_teardown_noop_total 70001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 139885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142575
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.509050
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142575
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 671
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 2116
telemt_me_writer_restored_fallback_total 137
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 8997141
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 157600827460 (146.78 GB)
telemt_user_octets_to_client{user="hello"} 3506111993202 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 56
```