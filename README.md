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

# Server Metrics 2026-03-22 16:24:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 69484.9 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2456403
telemt_connections_bad_total 131167
telemt_connections_current 1350
telemt_connections_me_current 1350
telemt_handshake_timeouts_total 87762
telemt_upstream_connect_attempt_total 25716
telemt_upstream_connect_success_total 25715
telemt_upstream_connect_attempts_per_request{bucket="1"} 25715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1037
telemt_me_reconnect_success_total 443
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 1982674
telemt_me_route_drop_channel_closed_total 815
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2091591
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 474
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 542
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 10109
telemt_desync_full_logged_total 3162
telemt_desync_suppressed_total 6947
telemt_desync_frames_bucket_total{bucket="1_2"} 2697
telemt_desync_frames_bucket_total{bucket="3_10"} 3790
telemt_desync_frames_bucket_total{bucket="gt_10"} 3622
telemt_pool_swap_total 77
telemt_pool_force_close_total 2383
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 463
telemt_me_draining_writers_reap_progress_total 23482
telemt_me_writer_removed_unexpected_total 432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1719
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21982
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21099
telemt_me_writer_teardown_success_total{mode="normal"} 23701
telemt_me_writer_teardown_noop_total 23488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47189
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.861090
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47189
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 463
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 393
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2088144
telemt_user_connections_current{user="hello"} 1350
telemt_user_octets_from_client{user="hello"} 31663778976 (29.49 GB)
telemt_user_octets_to_client{user="hello"} 557175458120 (518.91 GB)
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 82850.9 (23h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3597009
telemt_connections_bad_total 327432
telemt_connections_current 1269
telemt_connections_me_current 1269
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 89231
telemt_upstream_connect_attempt_total 52057
telemt_upstream_connect_success_total 51426
telemt_upstream_connect_fail_total 559
telemt_upstream_connect_attempts_per_request{bucket="1"} 51985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 559
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6051
telemt_me_reconnect_success_total 2188
telemt_me_reader_eof_total 2131
telemt_me_idle_close_by_peer_total 2131
telemt_me_route_drop_no_conn_total 3531062
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2850125
telemt_me_endpoint_quarantine_total 663
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 637
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 10
telemt_desync_total 11120
telemt_desync_full_logged_total 6199
telemt_desync_suppressed_total 4921
telemt_desync_frames_bucket_total{bucket="1_2"} 2590
telemt_desync_frames_bucket_total{bucket="3_10"} 4362
telemt_desync_frames_bucket_total{bucket="gt_10"} 4168
telemt_pool_swap_total 77
telemt_pool_force_close_total 2318
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 196
telemt_me_draining_writers_reap_progress_total 32990
telemt_me_writer_removed_unexpected_total 2086
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3962
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31120
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1962
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30672
telemt_me_writer_teardown_success_total{mode="normal"} 35082
telemt_me_writer_teardown_noop_total 32990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68072
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.879862
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68072
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 196
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1898
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 2861406
telemt_user_connections_current{user="hello"} 1269
telemt_user_octets_from_client{user="hello"} 35588002611 (33.14 GB)
telemt_user_octets_to_client{user="hello"} 636765507798 (593.03 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 157710.8 (43h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15314825
telemt_connections_bad_total 1429139
telemt_connections_current 1934
telemt_connections_me_current 1934
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 372394
telemt_upstream_connect_attempt_total 71287
telemt_upstream_connect_success_total 71192
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 71209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1673
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2664
telemt_me_reconnect_success_total 1357
telemt_me_reader_eof_total 1296
telemt_me_idle_close_by_peer_total 1294
telemt_me_route_drop_no_conn_total 13803242
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12237274
telemt_me_endpoint_quarantine_total 993
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1178
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
telemt_me_writers_active_current 46
telemt_desync_total 49827
telemt_desync_full_logged_total 15633
telemt_desync_suppressed_total 34194
telemt_desync_frames_bucket_total{bucket="1_2"} 11163
telemt_desync_frames_bucket_total{bucket="3_10"} 19473
telemt_desync_frames_bucket_total{bucket="gt_10"} 19191
telemt_pool_swap_total 170
telemt_pool_force_close_total 5794
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 939
telemt_me_draining_writers_reap_progress_total 51896
telemt_me_writer_removed_unexpected_total 1250
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4525
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47913
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46102
telemt_me_writer_teardown_success_total{mode="normal"} 52438
telemt_me_writer_teardown_noop_total 51946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104384
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 298.933939
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104384
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 939
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1164
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 12238447
telemt_user_connections_current{user="hello"} 1934
telemt_user_octets_from_client{user="hello"} 173329968589 (161.43 GB)
telemt_user_octets_to_client{user="hello"} 3162625709379 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 713
telemt_user_unique_ips_recent_window{user="hello"} 705
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 157712.2 (43h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11048713
telemt_connections_bad_total 1072081
telemt_connections_current 1215
telemt_connections_me_current 1215
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 327768
telemt_upstream_connect_attempt_total 83463
telemt_upstream_connect_success_total 82307
telemt_upstream_connect_fail_total 832
telemt_upstream_connect_attempts_per_request{bucket="1"} 83139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3695
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 832
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3934
telemt_me_reconnect_success_total 1598
telemt_me_reader_eof_total 1469
telemt_me_idle_close_by_peer_total 1469
telemt_me_route_drop_no_conn_total 4358646
telemt_me_route_drop_channel_closed_total 478
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8240059
telemt_me_endpoint_quarantine_total 993
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1194
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
telemt_me_writers_active_current 44
telemt_desync_total 36596
telemt_desync_full_logged_total 12297
telemt_desync_suppressed_total 24299
telemt_desync_frames_bucket_total{bucket="1_2"} 8972
telemt_desync_frames_bucket_total{bucket="3_10"} 14110
telemt_desync_frames_bucket_total{bucket="gt_10"} 13514
telemt_pool_swap_total 168
telemt_pool_force_close_total 5212
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 50170
telemt_me_writer_removed_unexpected_total 1498
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4627
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4736
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44958
telemt_me_writer_teardown_success_total{mode="normal"} 51528
telemt_me_writer_teardown_noop_total 50188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101716
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.268653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101716
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1360
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8178747
telemt_user_connections_current{user="hello"} 1215
telemt_user_octets_from_client{user="hello"} 204425587221 (190.39 GB)
telemt_user_octets_to_client{user="hello"} 3688717111306 (3.35 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 157677.5 (43h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10445392
telemt_connections_bad_total 898239
telemt_connections_current 1496
telemt_connections_me_current 1496
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 333438
telemt_upstream_connect_attempt_total 68648
telemt_upstream_connect_success_total 67697
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2073
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4670
telemt_me_reconnect_success_total 1887
telemt_me_reader_eof_total 1643
telemt_me_idle_close_by_peer_total 1642
telemt_me_route_drop_no_conn_total 5130810
telemt_me_route_drop_channel_closed_total 358
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7888807
telemt_me_endpoint_quarantine_total 1080
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1156
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_me_writers_active_current 41
telemt_desync_total 36137
telemt_desync_full_logged_total 11973
telemt_desync_suppressed_total 24164
telemt_desync_frames_bucket_total{bucket="1_2"} 9143
telemt_desync_frames_bucket_total{bucket="3_10"} 13814
telemt_desync_frames_bucket_total{bucket="gt_10"} 13180
telemt_pool_swap_total 165
telemt_pool_force_close_total 5135
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 50515
telemt_me_writer_removed_unexpected_total 1783
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47152
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4593
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45380
telemt_me_writer_teardown_success_total{mode="normal"} 52210
telemt_me_writer_teardown_noop_total 50586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102796
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.537368
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102796
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1633
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 7881784
telemt_user_connections_current{user="hello"} 1496
telemt_user_octets_from_client{user="hello"} 181658821197 (169.18 GB)
telemt_user_octets_to_client{user="hello"} 3276140631985 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 27956.3 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10142828
telemt_connections_bad_total 619971
telemt_connections_current 2368
telemt_connections_me_current 2368
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 187107
telemt_upstream_connect_attempt_total 35697
telemt_upstream_connect_success_total 33907
telemt_upstream_connect_fail_total 1253
telemt_upstream_connect_attempts_per_request{bucket="1"} 35160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5299
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1253
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5881
telemt_me_reconnect_success_total 703
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 24927840
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8443954
telemt_me_endpoint_quarantine_total 171
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 216
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 20
telemt_desync_total 13206
telemt_desync_full_logged_total 3405
telemt_desync_suppressed_total 9801
telemt_desync_frames_bucket_total{bucket="1_2"} 2350
telemt_desync_frames_bucket_total{bucket="3_10"} 5373
telemt_desync_frames_bucket_total{bucket="gt_10"} 5483
telemt_pool_swap_total 26
telemt_pool_force_close_total 1039
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 362
telemt_me_draining_writers_reap_progress_total 7615
telemt_me_writer_removed_unexpected_total 607
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1257
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6929
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 759
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6576
telemt_me_writer_teardown_success_total{mode="normal"} 8186
telemt_me_writer_teardown_noop_total 7620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15806
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.614197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15806
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 362
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 479
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8462091
telemt_user_connections_current{user="hello"} 2368
telemt_user_octets_from_client{user="hello"} 62790296110 (58.48 GB)
telemt_user_octets_to_client{user="hello"} 299903498700 (279.31 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 807
telemt_user_unique_ips_recent_window{user="hello"} 337
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 157682.9 (43h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10236069
telemt_connections_bad_total 857718
telemt_connections_current 1943
telemt_connections_me_current 1943
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 227433
telemt_upstream_connect_attempt_total 97419
telemt_upstream_connect_success_total 96429
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 97272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71832
telemt_me_reconnect_success_total 2612
telemt_me_reader_eof_total 2316
telemt_me_idle_close_by_peer_total 2315
telemt_me_route_drop_no_conn_total 5058943
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8071323
telemt_me_endpoint_quarantine_total 1065
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1176
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
telemt_desync_total 42071
telemt_desync_full_logged_total 14357
telemt_desync_suppressed_total 27714
telemt_desync_frames_bucket_total{bucket="1_2"} 8564
telemt_desync_frames_bucket_total{bucket="3_10"} 16265
telemt_desync_frames_bucket_total{bucket="gt_10"} 17242
telemt_pool_swap_total 161
telemt_pool_force_close_total 4763
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 601
telemt_me_draining_writers_reap_progress_total 53647
telemt_me_writer_removed_unexpected_total 2359
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5737
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50290
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48884
telemt_me_writer_teardown_success_total{mode="normal"} 56027
telemt_me_writer_teardown_noop_total 53648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109675
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.449485
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109675
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 601
telemt_me_refill_failed_total 4268
telemt_me_writer_restored_same_endpoint_total 2193
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8075298
telemt_user_connections_current{user="hello"} 1943
telemt_user_octets_from_client{user="hello"} 182969572265 (170.40 GB)
telemt_user_octets_to_client{user="hello"} 3041628614988 (2.77 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 94519.1 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10649567
telemt_connections_bad_total 398609
telemt_connections_current 1407
telemt_connections_me_current 1407
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4474706
telemt_upstream_connect_attempt_total 45487
telemt_upstream_connect_success_total 45157
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 45478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_reconnect_attempts_total 48067
telemt_me_reconnect_success_total 1514
telemt_me_reader_eof_total 1178
telemt_me_idle_close_by_peer_total 1177
telemt_me_route_drop_no_conn_total 3915308
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5104030
telemt_me_endpoint_quarantine_total 614
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 708
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27983
telemt_desync_full_logged_total 9459
telemt_desync_suppressed_total 18524
telemt_desync_frames_bucket_total{bucket="1_2"} 5634
telemt_desync_frames_bucket_total{bucket="3_10"} 11036
telemt_desync_frames_bucket_total{bucket="gt_10"} 11313
telemt_pool_swap_total 99
telemt_pool_force_close_total 3055
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 32485
telemt_me_writer_removed_unexpected_total 1241
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2917
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30839
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2636
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29430
telemt_me_writer_teardown_success_total{mode="normal"} 33756
telemt_me_writer_teardown_noop_total 32492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66248
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.878949
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66248
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 2706
telemt_me_writer_restored_same_endpoint_total 1347
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5097576
telemt_user_connections_current{user="hello"} 1407
telemt_user_octets_from_client{user="hello"} 109734952380 (102.20 GB)
telemt_user_octets_to_client{user="hello"} 1925395353750 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 75489.8 (20h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014113
telemt_connections_bad_total 14928
telemt_connections_current 1178
telemt_connections_me_current 1178
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 19362
telemt_upstream_connect_attempt_total 37107
telemt_upstream_connect_success_total 37012
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 37090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 525
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1718
telemt_me_reconnect_success_total 711
telemt_me_reader_eof_total 685
telemt_me_idle_close_by_peer_total 685
telemt_me_route_drop_no_conn_total 354885
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 903103
telemt_me_endpoint_quarantine_total 647
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 625
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
telemt_me_writers_active_current 45
telemt_desync_total 5030
telemt_desync_full_logged_total 1547
telemt_desync_suppressed_total 3483
telemt_desync_frames_bucket_total{bucket="1_2"} 1194
telemt_desync_frames_bucket_total{bucket="3_10"} 2005
telemt_desync_frames_bucket_total{bucket="gt_10"} 1831
telemt_pool_swap_total 80
telemt_pool_force_close_total 2023
telemt_me_writer_close_signal_drop_total 119
telemt_me_draining_writers_reap_progress_total 30727
telemt_me_writer_removed_unexpected_total 662
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29036
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1943
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28704
telemt_me_writer_teardown_success_total{mode="normal"} 31414
telemt_me_writer_teardown_noop_total 30730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62144
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.735289
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62144
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 119
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 604
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 899655
telemt_user_connections_current{user="hello"} 1178
telemt_user_octets_from_client{user="hello"} 16145066997 (15.04 GB)
telemt_user_octets_to_client{user="hello"} 398915581631 (371.52 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 157687.7 (43h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12506491
telemt_connections_bad_total 1448646
telemt_connections_current 1898
telemt_connections_me_current 1898
telemt_handshake_timeouts_total 344991
telemt_upstream_connect_attempt_total 59254
telemt_upstream_connect_success_total 59019
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 59200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_reconnect_attempts_total 2337
telemt_me_reconnect_success_total 1233
telemt_me_reader_eof_total 1197
telemt_me_idle_close_by_peer_total 1197
telemt_me_route_drop_no_conn_total 4172983
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9457850
telemt_me_endpoint_quarantine_total 1069
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1179
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 38796
telemt_desync_full_logged_total 12669
telemt_desync_suppressed_total 26127
telemt_desync_frames_bucket_total{bucket="1_2"} 9222
telemt_desync_frames_bucket_total{bucket="3_10"} 14376
telemt_desync_frames_bucket_total{bucket="gt_10"} 15198
telemt_pool_swap_total 175
telemt_pool_force_close_total 4804
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 53334
telemt_me_writer_removed_unexpected_total 1150
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4370
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50147
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4631
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48530
telemt_me_writer_teardown_success_total{mode="normal"} 54517
telemt_me_writer_teardown_noop_total 53336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.073659
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 1077
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 9427100
telemt_user_connections_current{user="hello"} 1898
telemt_user_octets_from_client{user="hello"} 184902637336 (172.20 GB)
telemt_user_octets_to_client{user="hello"} 4162227934940 (3.79 TB)
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 157684.5 (43h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10842847
telemt_connections_bad_total 1212494
telemt_connections_current 1541
telemt_connections_me_current 1541
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 280000
telemt_upstream_connect_attempt_total 85030
telemt_upstream_connect_success_total 84389
telemt_upstream_connect_fail_total 554
telemt_upstream_connect_attempts_per_request{bucket="1"} 84943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2029
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 554
telemt_me_reconnect_attempts_total 8941
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 1921
telemt_me_idle_close_by_peer_total 1921
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5416013
telemt_me_route_drop_channel_closed_total 347
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8382169
telemt_me_endpoint_quarantine_total 1201
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1181
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38253
telemt_desync_full_logged_total 12356
telemt_desync_suppressed_total 25897
telemt_desync_frames_bucket_total{bucket="1_2"} 9511
telemt_desync_frames_bucket_total{bucket="3_10"} 14261
telemt_desync_frames_bucket_total{bucket="gt_10"} 14481
telemt_pool_swap_total 167
telemt_pool_force_close_total 4650
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 605
telemt_me_draining_writers_reap_progress_total 52797
telemt_me_writer_removed_unexpected_total 1946
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5470
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49342
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48147
telemt_me_writer_teardown_success_total{mode="normal"} 54812
telemt_me_writer_teardown_noop_total 52802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107614
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.497581
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107614
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 605
telemt_me_refill_failed_total 353
telemt_me_writer_restored_same_endpoint_total 1672
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 8388161
telemt_user_connections_current{user="hello"} 1541
telemt_user_octets_from_client{user="hello"} 147617000801 (137.48 GB)
telemt_user_octets_to_client{user="hello"} 3204832951363 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 210
```